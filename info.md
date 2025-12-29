# Product Overview

This is a Retrieval-Augmented Generation (RAG) system that enables question-answering over Olympic Games knowledge. The system uses local LLMs via Ollama to provide contextual answers about Olympic history, athletes, controversies, and cultural significance.

## Key Features

- **Document Processing**: Loads and chunks text documents for vector storage
- **Vector Search**: Uses FAISS for efficient similarity search over embedded content
- **Local LLM Integration**: Leverages Ollama for both embeddings and text generation
- **Caching**: Implements SQLite caching for improved response times
- **Interactive CLI**: Command-line interface for real-time question answering

## Use Cases

- Educational tool for Olympic Games knowledge
- Demonstration of RAG architecture patterns
- Local AI system without external API dependencies
