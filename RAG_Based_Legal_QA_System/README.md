#  RAG-Based Legal Question Answering System

##  Overview

This project is a **Retrieval-Augmented Generation (RAG)** based Legal Question Answering system designed to answer queries related to **Indian Central Acts**.

It combines semantic search with a generative language model to provide **accurate, context-aware, and citation-backed legal responses.**
##  Features
- Semantic search on legal documents
- Context-aware answer generation
- Reduced hallucination using RAG architecture
- Fast retrieval using vector database
- Supports natural language legal queries

## Tech Stack
- Embedding Model: all-MiniLM-L6-v2
- LLM Generator: FLAN-T5-Large
- Vector Database: ChromaDB
- Language: Python

## How It Works
- Legal documents are converted into embeddings.
- Stored in ChromaDB for semantic retrieval.
- User query is processed and matched with relevant documents.
- Retrieved context is sent to FLAN-T5 for answer generation.

## Dataset
- Annotated dataset of Indian Central Acts (1838–2020)
- Includes metadata like Act title, section, enactment date.

## Results
-Indexed Acts: 858
- Response Time: ~5–6 seconds
- Retrieval Accuracy: Nearly 95%

## Applications
- Legal research assistance
- Student learning tool
- Public legal awareness
- E-governance support systems

