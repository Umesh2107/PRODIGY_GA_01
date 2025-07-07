# 🧠 GPT-2 Text Generation with Fine-Tuning

This project demonstrates how to fine-tune the GPT-2 language model using a small custom dataset to generate human-like text based on a given prompt. The code is designed to run in **Google Colab** without requiring file uploads — everything is embedded directly.

---

## 🚀 Project Highlights

- ✅ Fine-tunes GPT-2 using a custom embedded dataset.
- ✅ Uses Hugging Face Transformers & Datasets.
- ✅ Runs fully in Google Colab with GPU acceleration.
- ✅ Text generation with sampling (top-k, top-p, temperature).
- ✅ No external files or API keys required.

---

## 📁 Folder Structure

GPT2_Text_Generation/
├── gpt2_finetune.ipynb # Colab-compatible notebook
└── README.md # This file

---

## 📚 Dependencies

Install these libraries inside Google Colab:

```python
!pip install transformers datasets accelerate
