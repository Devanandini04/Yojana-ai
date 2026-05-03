# 🧠 Yojana-AI

An AI-powered assistant that helps Indian citizens discover and check eligibility for government schemes using natural language.

---

## 🎯 Problem

India has 2500+ government schemes, but:

* People don’t know which schemes exist
* Government websites are complex
* Eligibility criteria are hard to understand
* No single platform to check eligibility
* Language barriers limit accessibility

As a result, many eligible citizens never claim the benefits they deserve.

---

## 💡 Solution

Yojana-AI is a conversational assistant that:

* Understands user queries in simple language (Hindi/English)
* Extracts user profile (age, income, state, etc.)
* Uses Retrieval-Augmented Generation (RAG) to find relevant schemes
* Shows only eligible schemes
* Provides clear explanations with official sources

---

## ⚙️ Tech Stack

* **Language:** Python
* **Framework:** LangChain
* **Vector Database:** ChromaDB
* **LLM:** Ollama (LLaMA / Mistral)
* **Embeddings:** Sentence Transformers
* **Frontend:** Streamlit

---

## 🏗️ Project Structure

```
Yojana-ai/
│
├── data/                  # Raw and processed scheme data
├── vectorstore/           # ChromaDB storage (ignored in git)
├── src/                   # Core logic
│   ├── ingest.py
│   ├── rag_chain.py
│   ├── eligibility.py
│   └── data_loader.py
│
├── app.py                 # Streamlit app
├── requirements.txt
└── README.md
```

---

## 🚀 Features (MVP)

* User profile-based scheme filtering
* RAG-based retrieval system
* Local LLM using Ollama
* Source-backed answers (no hallucination)
* Clean and simple output format

---

## 🔮 Future Scope

* Full database of 2500+ schemes
* Multilingual support (Hindi + regional languages)
* Voice input for rural accessibility
* Step-by-step application guidance
* WhatsApp bot integration

---

## 🏆 Why This Project

* Solves a real-world problem
* Demonstrates GenAI + RAG pipeline
* Combines AI + rule-based filtering
* Scalable and impactful

---

## 📌 Status

🚧 Currently in development — building MVP

---

## 👩‍💻 Author

**Deven**
Aspiring Developer | ML Enthusiast | Builder

---
