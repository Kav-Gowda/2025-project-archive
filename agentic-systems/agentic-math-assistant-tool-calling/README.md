# Agentic Math Assistant (Tool Calling)

## Overview

This project implements an LLM-based math assistant that solves problems using tool calling and agentic reasoning.

The system interprets natural language queries, selects appropriate mathematical tools, and executes multi-step reasoning workflows.

---

## What I Implemented

* Custom mathematical tools for arithmetic operations
* Agent-based reasoning using LangGraph (ReAct pattern)
* Tool selection and execution based on user queries
* Hybrid workflows combining retrieval and computation

---

## Tech Stack

* **Frameworks:** LangChain, LangGraph
* **Model:** Open-source LLM (HuggingFace)
* **Libraries:** Wikipedia API
* **Language:** Python

---

## How It Works

1. Receive a natural language query
2. Interpret intent and select the appropriate tool
3. Execute tool(s) using LangGraph agent workflow
4. Optionally retrieve external information (Wikipedia)
5. Return final answer with reasoning

---

## Key Features

* Tool-based mathematical reasoning
* ReAct-style agent workflow (LangGraph)
* Multi-step reasoning and tool orchestration
* Integration of retrieval with computation

---

## Files

* `agentic-math-assistant-tool-calling.ipynb` — main implementation
