# 💻 Code Assistant using Meta's CodeLlama (LangChain + Streamlit)

An intelligent coding assistant built using **LangChain** and **Meta's CodeLlama**, with a Streamlit UI for code completion, debugging help, and multilingual programming assistance.

---

## 📂 Project Structure

```
Codellama/
├── app.py         # Streamlit UI that interacts with the CodeLlama model
├── modelfile      # Local or hosted model reference file (path or API config)
└── requirements.txt
```

---

## 🚀 Features

- 🧠 Integrates LangChain with CodeLlama for programming tasks
- 🌐 Accepts prompts in Python, JavaScript, Java, and more
- 📋 Provides explanations, fixes, and code suggestions
- 🖥️ Interactive Streamlit UI

---

## 🛠️ How to Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

> ✅ Make sure the `modelfile` contains valid path/config to CodeLlama checkpoint or endpoint.

---

## 💬 Sample Prompts

- “Write a Python script to reverse a linked list.”
- “Fix this code: `for i in range(5) print(i)`”
- “Convert this Python code to Java.”

---

## 🔭 Future Improvements

- Add syntax highlighting and output execution
- Expand support for more languages (C++, Rust, Go)
- Integrate with VS Code as a plugin

---



## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aparna-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/aparna-k-628005167/)
