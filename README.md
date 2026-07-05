# RAG Model Validation for Banking Risk Documents

## Overview

This project demonstrates the development and evaluation of a Retrieval-Augmented Generation (RAG) application for banking risk documents. The system retrieves relevant information from regulatory documents and annual reports using a vector database before generating responses using a locally hosted Large Language Model (LLM).

An independent evaluation framework was developed to assess the performance of the RAG pipeline using embedding-based similarity metrics, retrieval accuracy, and hallucination analysis.

---

## Key Features

- PDF document ingestion and preprocessing
- Document chunking for efficient retrieval
- Semantic embeddings using BAAI BGE Small
- FAISS vector database for semantic search
- Retrieval-Augmented Generation (RAG)
- Embedding-based Evaluation Framework
- Hallucination Detection
- Benchmark-based Performance Evaluation

---

## Repository Structure

```text
notebooks/
    01_Building the RAG System.ipynb
    02_Evaluating the RAG Model.ipynb

outputs/
    rag_results.csv
    rag_results_final.csv

report/
    RAG_Prototype_Model Validation Doc (Raghav Mittal)
```

---

## Technology Stack

| Component | Technology |
|-----------|------------|
| Framework | LangChain |
| Embedding Model | BAAI/bge-small-en-v1.5 |
| Vector Database | FAISS |
| LLM | Microsoft Phi-3 Mini |
| Programming Language | Python |

---

## Project Workflow

PDF Documents → Document Chunking → Embedding Generation → FAISS Vector Database → User Query → Semantic Retrieval → Prompt Construction → LLM Response → Model Evaluation

---

## Evaluation Metrics

- Retrieval Accuracy
- Context Relevance
- Answer Relevance
- Answer Correctness
- Hallucination Rate
