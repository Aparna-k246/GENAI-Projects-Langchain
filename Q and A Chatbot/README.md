# 💬 Q and A Chatbots – OpenAI & Ollama (LangChain + Streamlit)

Two variants of question-answering chatbots built using **LangChain** with **Streamlit** UIs. One version uses **OpenAI APIs**, while the other runs locally via **Ollama** (LLaMA models). Both allow users to ask arbitrary questions and receive intelligent, contextual replies.

---

## 📂 Project Structure

```
Q and A Chatbot/
├── Ollama Chatbot/
│   └── app.py             # LangChain + LLaMA via Ollama
└── OpenAI Chatbot/
    └── app.py             # LangChain + OpenAI LLM (GPT-3.5/4)
```

---

## 🚀 Features

- 🧠 LangChain-based prompt handling and memory
- 🌐 `OpenAI Chatbot`: Uses GPT models via API
- 💻 `Ollama Chatbot`: Runs models like LLaMA3 locally via Ollama
- 🖥️ Both provide a minimal but working Streamlit UI

---

## 🛠️ How to Run

### For OpenAI Chatbot:
```bash
cd "Q and A Chatbot/OpenAI Chatbot"
pip install -r requirements.txt
streamlit run app.py
```
> 🔐 Requires OpenAI API key set via environment variable or `.env`.

---

### For Ollama Chatbot:
```bash
cd "Q and A Chatbot/Ollama Chatbot"
pip install -r requirements.txt
streamlit run app.py
```
> 💡 Requires [Ollama](https://ollama.com) installed locally and a model (like `llama3`) pulled.

---

## 💬 Example Questions

- “What is the capital of Australia?”
- “Explain how LangChain memory works.”
- “Give me a Python function to reverse a string.”

---

## 🔭 Future Improvements

- Add chat history storage
- Combine both bots in a single UI with model selector
- Support speech-to-text input



---

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aparna-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/aparna-k-628005167/)
