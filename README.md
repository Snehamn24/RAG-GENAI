# 📚 RAG-Wikipedia-GenAI

## 🚀 Overview

This project implements a **Retrieval-Augmented Generation (RAG)** system that answers user queries using real-time knowledge from Wikipedia.

It combines:

* Information retrieval
* Semantic search
* Large Language Models (LLMs)

👉 This project demonstrates how modern AI systems reduce hallucinations by grounding responses in real data.

---

## 🧠 How it Works

1. Fetch data from Wikipedia
2. Split text into chunks
3. Convert text into embeddings
4. Store embeddings in ChromaDB
5. Retrieve relevant chunks
6. Generate answers using LLM

---

## 🛠️ Tech Stack

* Python
* LangChain
* ChromaDB
* HuggingFace Embeddings
* OpenRouter (LLM API)

---

## 📌 Features

* Dynamic Wikipedia data loading
* Semantic search using embeddings
* Context-aware answer generation
* Modular and scalable RAG pipeline

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/RAG-Wikipedia-GenAI.git
cd RAG-Wikipedia-GenAI
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Add API Key

Create a `.env` file:

```
OPENAI_API_KEY=your_api_key_here
```

### 4. Run the project

```bash
python main.py
```

---

## 💡 Example Query

```
Explain Generative AI in simple terms
```

---

## 📈 Future Improvements

* Add chatbot UI
* Support PDF/document upload
* Multi-source RAG (web + docs)
* Deploy using FastAPI

---

## 👩‍💻 Author

**Sneha M N**
