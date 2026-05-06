# 🏦 AI-Powered Bank Product Recommendation System

An AI-powered financial recommendation platform built using Django, FAISS, Retrieval-Augmented Generation (RAG), and LLMs to provide personalized banking and financial product recommendations.

This project combines structured financial product data with semantic retrieval from financial documents to generate context-aware recommendations and insights.

---

# Features

- Retrieval-Augmented Generation (RAG)
- Semantic Search using FAISS
- PDF-based knowledge retrieval
- Personalized financial recommendations
- Django REST APIs
- Streamlit dashboard
- LLM-powered response generation

---

# System Architecture

```text
User
  ↓
Streamlit Frontend
  ↓
Django Backend APIs
  ↓
RAG Pipeline + Product Database
  ↓
FAISS Vector Search
  ↓
LLM Response Generation
```

---

## Tech Stack

**Backend**
- Django
- Django ORM

**Frontend**
- Streamlit
- Plotly

**AI / RAG**
- Sentence Transformers
- FAISS
- Groq API
- LLaMA 3

---

# RAG Workflow

```text
PDF Documents
      ↓
Text Chunking
      ↓
Embeddings Generation
      ↓
FAISS Vector Store
      ↓
Semantic Retrieval
      ↓
LLM Context Injection
      ↓
Generated Response
```

---

# API Endpoints

## `/recommend/`
Returns filtered financial products based on user profile.

## `/ask/`
Combines product filtering, semantic retrieval, and LLM response generation.

---

# Engineering Work

- PDF ingestion and chunking pipeline
- Embedding generation using Sentence Transformers
- FAISS vector database integration
- Semantic retrieval workflow
- RAG integration with Django APIs

---

# Example Capabilities

- Investment recommendations
- Loan and insurance guidance
- Financial document query handling
- Personalized financial insights

---

# Team Project

This repository is part of a collaborative group project.

My primary contribution focused on:

- RAG pipeline development
- Semantic retrieval system
- Embeddings and FAISS integration
- AI workflow integration
