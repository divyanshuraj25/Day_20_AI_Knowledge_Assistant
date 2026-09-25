# 🤖 Day 20 — AI Knowledge Assistant

A RAG-based AI Knowledge Assistant built as part of my **60 Days AI/ML Challenge**.

This project combines semantic search, metadata filtering, grounded prompting, Gemini, FAISS, and FastAPI to create an AI assistant that answers questions using information retrieved from a knowledge base.

---

## 🚀 Project Overview

The AI Knowledge Assistant follows a Retrieval-Augmented Generation (RAG) workflow:

```text
User Query
    ↓
Semantic Search
    ↓
FAISS Retrieval
    ↓
Metadata Filtering
    ↓
Relevant Context
    ↓
Grounded Gemini Prompt
    ↓
AI Answer + Sources
    ↓
Confidence Check
