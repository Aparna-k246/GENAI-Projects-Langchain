# 📝 Text Summarization App (LangChain + Streamlit + PDF/Web/YouTube)

An app that summarizes **PDF files**, **YouTube videos**, or **webpages** using **LangChain** and LLMs. Designed with a **Streamlit UI**, this project allows users to extract the core ideas from long content using Retrieval-Augmented Generation (RAG).

---

## 📂 Project Structure

```
Text Summarization/
├── apjspeech.pdf             # Sample PDF input
├── app.py                    # Streamlit UI for multi-source summarization
├── text_summarization.ipynb  # Notebook for step-by-step experimentation
└── requirements.txt
```

---

## 🚀 Features

- 📄 Summarize PDF documents (local or uploaded)
- 🎥 Extract and summarize content from YouTube transcripts
- 🌐 Summarize web content by providing a URL
- 🤖 Uses LangChain chains + memory + prompts

---

## 🛠️ How to Run

```bash
cd "Text Summarization"
pip install -r requirements.txt
streamlit run app.py
```

> 📌 Ensure any keys (e.g., OpenAI) are stored in `.env` or set in your environment.

---

## 💬 Example Use Cases

- Upload an academic paper and get a 3-sentence summary
- Paste a YouTube link and extract key points
- Enter a blog/article URL for TL;DR

---

## 🔭 Future Improvements

- Add extractive + abstractive summary mode
- Visualize summaries as key bullet points
- Support multi-PDF or batch processing

---

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aparna-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/aparna-k-628005167/)
