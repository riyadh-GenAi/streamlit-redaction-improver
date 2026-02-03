# ✍️ AI Text Redaction Improver (Streamlit Demo)

A simple Streamlit application that rewrites draft text into different **tones** and **English dialects** using **Groq LLMs** via LangChain.

This project was built as a **learning / practice app** while exploring AI application development and prompt-based text transformation.

---

## 🚀 Features
- Rewrite text in **Formal** or **Informal** tone  
- Choose English dialect: **American** or **British**  
- Uses **Groq (LLaMA 3.1)** for fast inference  
- Clean and interactive **Streamlit UI**

---

## 🧠 Tech Stack
- Python 3.11
- Streamlit
- LangChain
- Groq API (`llama-3.1-8b-instant`)
- Poetry for dependency management

---

## ▶️ Run Locally

```bash
poetry install
poetry shell
streamlit run main.py
