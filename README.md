# 🎨 Text-to-Image Generator

![Project Status](https://img.shields.io/badge/Status-Completed-success) 
![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Overview
This project is a generative AI web application that creates high-quality images from textual descriptions. It leverages the power of **Stable Diffusion v1.5** to convert text prompts into detailed visual art. 

**Internship Context:** This project was developed as **Task-02** during my Machine Learning Internship at **Prodigy Infotech**, demonstrating the practical implementation of pre-trained generative models and web UI integration.

*Here’s the main interface of the Text Generation with GPT-2:*

![img]()

## ✨ Features
* **Intuitive Web Interface:** Built with Gradio for seamless, browser-based interaction.
* **Advanced Prompting:** Supports both positive and negative prompts to fine-tune image generation.
* **Customizable Parameters:** Allows users to adjust inference steps and guidance scale (CFG) for optimal quality.
* **Reproducibility:** Seed control ensures the ability to recreate specific generations.
* **GPU Accelerated:** Optimised for rapid generation using PyTorch and CUDA.

## 🛠️ Tech Stack
* **Language:** Python 3.8+
* **Core Frameworks:** PyTorch
* **AI Libraries:** Hugging Face `diffusers`, `transformers`, `accelerate`
* **Model:** RunwayML Stable Diffusion v1-5
* **Frontend UI:** Gradio
* **Environment:** Google Colab (T4 GPU) / Local Virtual Environment

## 🚀 Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Dharmendra0305/PRODIGY_GA_02.git](https://github.com/Dharmendra0305/PRODIGY_GA_02.git)

2. **Create and activate a virtual environment:**
   - Windows:
     ```bash
     python -m venv venv
     venv\Scripts\activate

   - Mac/Linux:
     ```bash
     python3 -m venv venv
     source venv/bin/activate

3. Install dependencies:
   ```bash
   pip install torch diffusers transformers accelerate gradio

## 💻 Usage
1. Run the application:
   (Ensure you save the Python code provided previously into a file named app.py)
   ```bash
   python app.py

2. Access the Web UI:
   - The terminal will output a local URL (e.g., http://127.0.0.1:7860).
   - If share=True is enabled in the code, a public gradio.live link will also be generated.

## 🤝 Contribution Guidelines
Contributions are welcome! If you'd like to improve the code or add features:
1. Fork the repository.
2. Create a new branch (git checkout -b feature/AmazingFeature).
3. Commit your changes (git commit -m 'Add some AmazingFeature').
4. Push to the branch (git push origin feature/AmazingFeature).
5. Open a Pull Request.

📄 License
Distributed under the MIT License. See [LICENSE](LICENSE) for more information.
