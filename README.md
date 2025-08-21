# Postwriter with LangChain, LangGraph & ReAct

This repo contains a **Colab notebook** that demonstrates how to build and evaluate **LLM-powered workflows** using LangChain, LangGraph, and Nebius-hosted LLMs (Qwen3-235B).

## What’s inside
- **Baseline LLM call** – generate LinkedIn-style posts with prompt engineering.  
- **LangGraph workflow** – build a graph to:
  - Search TechCrunch
  - Scrape article content
  - Convert text → LinkedIn post  
- **ReAct agent** – convert workflow into an agent with:
  - Tools (search, scrape, writer)
  - Memory (`ConversationBufferMemory`)
  - Interactive reasoning and tool selection  
- **LangSmith integration** – tracing & monitoring of runs (just an example, didn't fully integrate)
