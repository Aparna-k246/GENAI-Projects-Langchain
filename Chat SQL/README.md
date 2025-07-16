# 🧮 Chat SQL Bot (LangChain + SQLite + Streamlit)

An interactive chatbot powered by LangChain that connects to a **SQLite database** (`student.db`) and lets users query it in natural language via a **Streamlit UI**. The system automatically converts questions into executable SQL queries and returns the results.

---

## 📂 Project Structure

```
Chat SQL/
├── app.py          # Streamlit interface + LangChain SQL agent
├── sqlite.py       # DB connector and agent tools
└── student.db      # Sample student database (SQLite)
```

---

## 🚀 Features

- 🧠 Uses LangChain’s SQLDatabaseToolkit
- 💬 Accepts natural language input from a Streamlit form
- 🔎 Auto-generates and executes SQL queries
- 📊 Displays result directly in the app interface

---

## 🛠️ How to Run

```bash
pip install -r requirements.txt  # if available
streamlit run app.py
```

> ⚠️ Make sure `student.db` exists in the same directory and follows the expected schema.

---

## 💡 Example Queries

- “List all students who scored more than 90”
- “What is the average mark in the class?”

---

## 🔭 Future Enhancements

- Export query results to CSV
- Add authentication and chat history
- Extend to support other DBs (MySQL, PostgreSQL)

---


## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aparna-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/aparna-k-628005167/)
