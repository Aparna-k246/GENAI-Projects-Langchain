# 🗣️ RAG Q&A Conversation Bot (LangChain + Streamlit + PDF + Memory)

An interactive, **conversational chatbot** that performs Retrieval-Augmented Generation (RAG) over a PDF document using **LangChain**, with **chat history support** and a clean **Streamlit UI**. Ask follow-up questions and get contextually aware answers using local document data.

---

## 📂 Project Structure

```
RAG Q&A Conversation/
├── app.py         # Streamlit app with PDF upload, vector search, and chat memory
└── temp.pdf       # Sample document for testing
```

---

## 🚀 Features

- 📄 Upload and query PDFs using LangChain’s document loaders
- 🧠 Maintains conversation history using LangChain memory
- 🔍 Retrieves contextually relevant chunks via retriever
- 🤖 Generates responses using OpenAI or other LLMs
- 🌐 Streamlit interface with real-time Q&A

---

## 🛠️ How to Run

```bash
cd "RAG Q&A Conversation"
pip install -r requirements.txt
streamlit run app.py
```

> 📎 Replace `temp.pdf` with your own document or allow uploads in the UI.

---

## 💬 Example Conversation

- **You**: “What’s this document about?”
- **Bot**: “It discusses neural network attention mechanisms...”
- **You**: “Explain the use of softmax here.”

---

## 🔭 Future Enhancements

- Add PDF uploader to replace hardcoded file
- Enable multi-file RAG
- Support local LLMs (e.g., Ollama) for private use

---


## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aparna-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/aparna-k-628005167/)
