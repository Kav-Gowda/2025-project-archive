# Secure Document Summarization using RAG

## Overview

This project implements a Retrieval-Augmented Generation (RAG) system for summarizing and answering questions over private documents.

The system processes confidential text data locally, retrieves relevant context, and generates grounded responses without exposing sensitive information.

---

## What I Implemented

* RAG pipeline for private document understanding
* Document chunking and embedding generation
* Vector storage and retrieval using ChromaDB
* Conversational Q&A with memory for multi-turn interactions

---

## Tech Stack

* **LLM:** Llama 3.3 (watsonx.ai)
* **Framework:** LangChain
* **Embeddings:** HuggingFace Sentence Transformers
* **Vector Store:** ChromaDB
* **Language:** Python

---

## How It Works

1. Load and preprocess private documents
2. Split text into chunks
3. Generate embeddings
4. Store embeddings in ChromaDB
5. Retrieve relevant context
6. Generate answers using LLM with conversational memory

---

## Key Features

* Secure processing of private documents
* Retrieval-based summarization and Q&A
* Multi-turn conversational memory
* Grounded responses using retrieved context

---

## Files

* `secure-document-summarization-rag.ipynb` — main implementation
