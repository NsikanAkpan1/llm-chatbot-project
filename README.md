# LLM-Based Chatbot (RAG Pipeline)

## Overview
This project implements a Retrieval-Augmented Generation (RAG) chatbot using a Large Language Model (LLM). The system retrieves relevant documents from a vector database and uses them as context to generate accurate, grounded responses.

This project was developed as part of my MSc in Automation Control and Robotics.

## Architecture
- Document loading and preprocessing
- Text chunking using recursive character splitting
- Embedding generation using HuggingFace models
- Vector storage using FAISS
- Similarity-based document retrieval
- LLM-based response generation with prompt templates

## Technologies Used
- Python
- LangChain
- HuggingFace Transformers & Embeddings
- FAISS vector database
- LlamaCpp (local inference)
- NumPy, Pandas

## Key Features
- Domain-specific question answering
- Prompt engineering for controlled responses
- Similarity search over embedded documents
- Local LLM inference for privacy and efficiency

## Example Use Case
Users can ask questions related to the provided dataset, and the chatbot retrieves relevant context before generating concise answers.

## Notes
This is an academic project focused on learning and experimentation. The code reflects an iterative development process.
