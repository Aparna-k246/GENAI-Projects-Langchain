# 🤗 HuggingFace LLM Integration (LangChain + Streamlit)

This project demonstrates how to use **HuggingFace-hosted LLMs** via LangChain in a local app, enabling chat, code generation, and basic NLP tasks. The app uses a Streamlit UI and connects with public or private HuggingFace models.

---

## 📂 Project Structure

```
Huggingface with Langchain/
├── app.py               # Streamlit interface for chat/code prompts
├── experiments.ipynb    # Notebook for testing various models/prompts
└── requirements.txt     # Python dependencies
```

---

## 🚀 Features

- Integrates LangChain with **HuggingFace Inference API**
- Easily switch between text-generation models (e.g., Falcon, BLOOM, LLaMA)
- Chat-like prompt interface via Streamlit
- Experimental playground via Jupyter Notebook

---

## 🛠️ How to Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

> 🔐 Add your HuggingFace API key as an environment variable or `.env` file if needed.

---

## 💬 Sample Prompts

- “Explain how transformers work.”
- “Generate Python code to scrape a website.”
- “Summarize the following text…”

---

## 🔭 Future Improvements

- Add dropdown to select models dynamically
- Improve prompt templates with chains
- Add token usage and latency stats

---



## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aparna-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/aparna-k-628005167/)
