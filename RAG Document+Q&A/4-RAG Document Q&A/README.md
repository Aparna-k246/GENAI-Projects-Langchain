# 📚 RAG Document Q&A (LangChain + GROQ + LLaMA3 + Streamlit)

A Streamlit-based Q&A app that performs **Retrieval-Augmented Generation (RAG)** on research PDFs using **LangChain**, **GROQ’s LLaMA3**, and **HuggingFace embeddings**. Users upload PDFs and ask questions about the content interactively.

---

## 📂 Project Structure

```
RAG Document+Q&A/
└── 4-RAG Document Q&A/
    ├── research_papers/
    │   ├── Attention.pdf
    │   └── LLM.pdf
    ├── app_huggingfaceembedding.py   # Optional backend module
    └── main.py                       # Full Streamlit app
```

---

## 🚀 Features

- 📄 Uploads and parses research PDFs
- 📚 Embeds chunks using HuggingFace + FAISS
- 🤖 Uses GROQ’s LLaMA3 for contextual answers
- 🌐 Full Streamlit UI for asking questions

---

## 🛠️ How to Run

```bash
cd "RAG Document+Q&A/4-RAG Document Q&A"
pip install -r requirements.txt
streamlit run main.py
```

> 📎 Place your PDFs in `research_papers/` before running.

---

## 💬 Example Queries

- “What is the conclusion of the Attention paper?”
- “What models are compared in the LLM document?”

---

## 🔭 Future Enhancements

- Dynamic upload support
- Add chart/graph summarization
- Log past queries and responses

---



## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aparna-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/aparna-k-628005167/)
