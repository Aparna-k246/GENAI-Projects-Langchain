# 🔍 AI-Powered Search Engine (LangChain + Tools + Agents)

This project builds a minimal **AI search engine** using **LangChain** with **tool integration** and **agent chaining**. It can search documents, answer natural language questions, and reason using LangChain's toolkit features — all through a user-friendly **Streamlit** interface.

---

## 📂 Project Structure

```
Search Engine/
├── app.py               # Streamlit UI with input box + output panel
└── tools_agents.ipynb   # Notebook with LangChain agents + retriever experiments
```

---

## 🚀 Features

- 🔎 Uses LangChain retrievers + agents for question answering
- 🧠 Supports reasoning across multiple tools
- 🖥️ Streamlit app for asking natural language queries
- 🧪 Notebook for building and experimenting with agent chains

---

## 🛠️ How to Run

```bash
cd "Search Engine"
pip install -r requirements.txt
streamlit run app.py
```

> ⚙️ You may need an OpenAI or local model key depending on the LLM used in `app.py`.

---

## 💬 Example Prompts

- “Search and summarize LangChain's documentation.”
- “What’s the current AI trend in text summarization?”
- “Compare HuggingFace and OpenAI models.”

---

## 🔭 Future Enhancements

- Add browser tools (e.g. SerpAPI or Tavily)
- Integrate citation support
- Deploy to HuggingFace Spaces

---

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aparna-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/aparna-k-628005167/)
