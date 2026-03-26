# Web-Scale RAG Pipeline

## Overview

This project implements a Retrieval-Augmented Generation (RAG) pipeline that retrieves and summarizes information from web sources using Llama 3.1 and LangChain.

The system processes live web data, embeds it into a vector store, and generates grounded, context-aware responses.

---

## What I Implemented

* End-to-end RAG pipeline for web-based data
* Automated ingestion and preprocessing of web content
* Embedding and indexing using a vector database
* Retrieval-based response generation with LLM grounding

---

## Tech Stack

* **LLM:** Llama 3.1 (watsonx.ai)
* **Framework:** LangChain
* **Embeddings:** Watsonx (SLATE)
* **Vector Store:** ChromaDB
* **Language:** Python

---

## How It Works

1. Fetch text data from web sources
2. Clean and split content into chunks
3. Generate embeddings
4. Store embeddings in ChromaDB
5. Retrieve relevant context and generate answers using Llama 3.1

---

## Key Features

* Grounded responses using retrieved context
* Real-time processing of unstructured web data
* Modular pipeline (easily extendable to other sources/models)

---

## Files

* `web-scale-rag-pipeline.py` — core pipeline implementation

