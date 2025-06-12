
# LangGraph Agentic RAG 🧠📚

An experimental Retrieval-Augmented Generation (RAG) agent built using [LangGraph](https://github.com/langchain-ai/langgraph), designed to explore agentic workflows over documents. Inspired by Lilian Weng's research and blog posts on advanced prompting and autonomous LLMs.

## 🧩 What It Does

This project creates a RAG agent that:

- Loads and chunks documents from Lilian Weng's blog posts
- Embeds them using a token-aware chunking strategy
- Stores them in a vector index
- Uses LangGraph to define an agent workflow (e.g., Ask → Retrieve → Rerank → Answer)
- Uses a Cohere reranker and OpenAI (or any LLM) as the final response generator

## 📌 Notes

- 🔄 You can **swap the LLM** with [Gemma](https://huggingface.co/google/gemma), GPT-4, Claude, or any model compatible with [LangChain](https://docs.langchain.com/).
- 🧠 The **document set and prompt template** are modular and can be easily adapted for any other domain or use case.
- 🏗️ This setup can be **scaled** with local vector databases (e.g., FAISS, Chroma) or extended with **multi-agent graphs** for more advanced workflows.


