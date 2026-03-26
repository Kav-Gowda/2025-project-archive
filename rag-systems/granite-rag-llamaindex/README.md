# Granite RAG with LlamaIndex

## Overview

This project implements a Retrieval-Augmented Generation (RAG) system using IBM Granite 3 and LlamaIndex for querying private documents.

The system builds a vector index over document data and generates grounded, context-aware responses using LLM-based retrieval.

---

## What I Implemented

* Document indexing using LlamaIndex
* Chunking and embedding of private text data
* Vector-based retrieval using semantic search
* Context-aware answer generation with Granite 3

---

## Tech Stack

* **LLM:** Granite 3 (watsonx.ai)
* **Framework:** LlamaIndex
* **Embeddings:** watsonx (SLATE)
* **Language:** Python

---

## How It Works

1. Load and preprocess private documents
2. Split documents into nodes
3. Generate embeddings
4. Build a vector index using LlamaIndex
5. Retrieve relevant context
6. Generate responses using Granite 3

---

## Key Features

* Efficient document indexing and retrieval
* Grounded responses using vector search
* Integration of Granite 3 with LlamaIndex
* Modular pipeline for document-based QA

---

## Files

* `granite-rag-llamaindex.ipynb` — main implementation
