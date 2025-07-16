# 📄 PDF Query RAG (LangChain + AstraDB)

This project implements **Retrieval-Augmented Generation (RAG)** over PDF documents using **LangChain**, **AstraDB vector store**, and **HuggingFace/OpenAI** LLMs. Upload a PDF and ask questions — the app searches the content and returns accurate, contextual answers.

---

## 📂 Project Structure

```
PDF query RAG/
└── PDFQuery_LangChain.ipynb    # Jupyter notebook with RAG pipeline
```

---

## 🚀 Features

- 🧠 Embeds PDF content into vector DB using AstraDB
- 🔍 Retrieves relevant chunks based on user query
- 💬 Uses LLM to generate a final response based on context
- ✅ Fully implemented in a single Jupyter notebook

---

## 🛠️ How to Run

1. Open the notebook in Jupyter Lab or VS Code.
2. Set your environment variables (`ASTRA_DB`, `OPENAI_API_KEY`, etc.).
3. Run cells one by one to:
   - Upload and chunk PDF
   - Embed into AstraDB
   - Query and get answers

---

## 📎 Example Queries

- “What is the key idea discussed in this PDF?”
- “Summarize the introduction.”
- “List all references used.”

---

## 🔭 Future Improvements

- Wrap notebook into a Streamlit app
- Add support for multiple PDFs
- Allow local ChromaDB fallback

---



## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aparna-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/aparna-k-628005167/)
