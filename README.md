# genai_summarizer
This project is a quick-start implementation of a **Generative AI-based Summarizer** built using Hugging Face Transformers in Python. It uses `pipeline("summarization")` from HuggingFace to generate summaries for long-form text.
# 🧠 GenAI Summarizer with Transformers

This project is a quick-start implementation of a **Generative AI-based Summarizer** built using Hugging Face Transformers in Python. It uses `pipeline("summarization")` from HuggingFace to generate summaries for long-form text.

## 🔧 Tools & Tech
- Python
- Hugging Face Transformers
- Colab / Jupyter Notebook
- Pretrained model: `distilbart-cnn-12-6`

## ✨ Features
- Summarizes free text or pasted documents
- Built using pretrained generative models
- Easy to extend into web apps using Streamlit or Gradio

## 💡 Example
**Input**: 
> Hello I am Harini Prasad Vasisht. I am pursuing Masters in Data Analytics Engineering.

**Summary**:  
> Harini Prasad Vasisht is pursuing a Masters in Data Analytics Engineering.

## 📂 How to Run
```bash
!pip install transformers
