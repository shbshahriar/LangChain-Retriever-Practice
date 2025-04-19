#  LangChain Retriever Practice with Wikipedia, Vector Stores & MMR

This repository contains a set of **retriever-based practice examples** using the **LangChain** framework. It demonstrates how to work with different retriever types, vector stores, and configurations — such as **Wikipedia search**, **ChromaDB**, **FAISS**, **MultiQuery**, **MMR**, and **Contextual Compression**.

---

## 🧠 What You’ll Learn

- Using `WikipediaRetriever` for real-time knowledge lookup  
- Building vector store retrievers using **ChromaDB** and **FAISS**  
- Performing semantic and filtered search  
- Exploring **MMR (Maximal Marginal Relevance)** for diversity  
- Using **MultiQueryRetriever** to reformulate queries  
- Compressing results using **ContextualCompressionRetriever**

---

## 🛠️ Tech Stack

- **LangChain** – LLM-powered application framework  
- **Google Generative AI** – Embedding + LLMs  
- **ChromaDB** / **FAISS** – Vector databases  
- **Wikipedia API** – Real-time data retrieval  
- **Python 3.9+**

---

## 📦 Installation

Install all dependencies via:

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install langchain chromadb faiss-cpu wikipedia openai tiktoken pypdf \
langchain_openai langchain-community google-generativeai
```

---

## 🔑 Environment Setup

Before running any retriever examples, set your **Google API key**:

```python
import os
os.environ["GOOGLE_API_KEY"] = "your-api-key-here"
```

---

## 📁 Structure Overview

```
.
├── main.py                # Retriever examples in one script
├── my_chroma_db/          # Vector store (Chroma) persistence
├── requirements.txt       # All required dependencies
└── README.md              # You're reading it
```

---

## 🎯 Use Case Ideas

- Retrieval-Augmented Generation (RAG) practice  
- LLM apps with context-aware search  
- Semantic search for lecture notes, PDFs, or scraped data  
- Query reformulation and compression pipelines

---

## ✍️ Notes

This project is meant purely for **learning and experimentation** with LangChain’s retriever interfaces. It is not production-optimized — but gives a strong foundation for building retrieval-augmented apps.
