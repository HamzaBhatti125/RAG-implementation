# 🧠 Retrieval-Augmented Generation (RAG) – Data Preparation with Langchain

This project is the first part of a RAG (Retrieval-Augmented Generation) pipeline using [Langchain](https://www.langchain.com/) — focused on preparing and embedding custom data for future LLM-based querying.

> ✅ **Implemented: Data Preparation**  
> 🔍 **Next Up: Query & Generation**

---

## 📌 What is RAG?

**RAG (Retrieval-Augmented Generation)** is a powerful architecture for building intelligent applications over your own data using LLMs. It combines traditional information retrieval with LLM-based generation, enabling more accurate and grounded responses.

---

## 🧱 Part 1 – Data Preparation

This repo covers:

### 1. 🔍 Ingestion

Supports multiple data sources:
- PDFs
- Text files
- JSON
- URLs (web scraping)
- CSV, Excel

### 2. ✂️ Chunking

Text is split into manageable chunks using Langchain’s document loaders and text splitters, considering token limits.

### 3. 🧠 Embedding

Each chunk is converted into a vector using your choice of:
- OpenAI embeddings
- HuggingFace models
- LLaMA or Gemini

### 4. 🗃️ Vector Store

Embeddings are stored in a vector database for fast similarity-based retrieval. Currently supported:
- Pinecone
- ChromaDB (default, open-source)

---

## ⚙️ Tech Stack

- 🦜 Langchain
- 🧠 OpenAI Embeddings
- 🔍 ChromaDB
- 🐍 Python 3.10+

---
