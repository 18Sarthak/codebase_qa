# AI Codebase QA Engine

RAG system that reads GitHub repos and answers questions about code.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/18Sarthak/codebase-qa/blob/main/gitans.ipynb)

## Quick Start
1. Open Colab badge ↑
2. Add Groq API key to Secrets ()
3. Run all cells

## Features
- AST parsing (Tree-sitter)
- Semantic chunking
- Vector search (TF-IDF/OpenAI)
- Cited answers (file:line numbers)

## Requirements
- Python 3.11
- Groq API key (free)

## Tech Stack
Python | Tree-sitter | Qdrant | Groq | Pydantic
