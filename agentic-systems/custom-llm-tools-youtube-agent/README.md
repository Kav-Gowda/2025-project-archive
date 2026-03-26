# Custom LLM Tools YouTube Agent

## Overview

This project implements an LLM-based agent that interacts with YouTube data using custom tools and LangChain.

The agent can retrieve transcripts, search videos, extract metadata, and generate summaries by orchestrating multi-step tool calls.

---

## What I Implemented

* Custom tools for interacting with YouTube APIs and data sources
* LLM tool-calling using LangChain
* Multi-step reasoning using runnable pipelines
* Iterative tool execution for complex queries

---

## Tech Stack

* **Framework:** LangChain
* **Model:** OpenAI-compatible LLM (tool calling)
* **Libraries:** pytube, yt-dlp, youtube-transcript-api
* **Language:** Python

---

## How It Works

1. Receive a user query (e.g., summarize a video)
2. Extract relevant inputs (e.g., video ID)
3. Call appropriate tools (transcript, metadata, search)
4. Feed tool outputs back to the LLM
5. Generate a final, context-aware response

---

## Key Features

* Custom tool design using LangChain
* OpenAI-style tool calling
* Multi-step agent reasoning with runnable pipelines
* Real-world YouTube data integration

---

## Files

* `custom-llm-tools-youtube-agent.ipynb` — main agent implementation
