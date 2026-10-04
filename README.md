# Conversational RAG Q&A Agent

An end-to-end **Retrieval-Augmented Generation (RAG)** application that answers questions from complex unstructured PDFs with high contextual accuracy.

Built using **LangChain + OpenAI + ChromaDB**.

---

### Overview

This project processes large volumes of PDF documents, creates meaningful embeddings, stores them in a vector database, and generates accurate, grounded answers using Large Language Models. It is designed for real-world document Q&A use cases.

---

### Key Features

- Intelligent PDF ingestion and chunking
- Embedding-based semantic search
- Context-aware answer generation
- Optimized prompt engineering for better responses
- FastAPI backend with Docker support
- Handles 500+ complex unstructured PDFs

---

### Tech Stack

- **Python**
- **LangChain**
- **OpenAI API** (Embeddings + GPT)
- **ChromaDB** (Vector Database)
- **FastAPI**
- **Docker**
- **RecursiveCharacterTextSplitter**

---

### How It Works

1. PDFs are loaded and split into meaningful chunks  
2. Embeddings are generated using OpenAI and stored in ChromaDB  
3. User query is converted into an embedding  
4. Most relevant document chunks are retrieved  
5. LLM generates a grounded and context-aware response  

---

### Getting Started

```bash
git clone https://github.com/deepu21232729/conversational-rag-qa.git
cd conversational-rag-qa
pip install -r requirements.txt
