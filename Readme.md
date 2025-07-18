# Semantic Search using Transformer-based Algorithm

This project demonstrates how to build a semantic search engine using transformer-based sentence embeddings and FAISS for fast similarity search. The example uses arXiv paper summaries as the searchable dataset.

## Features

- Loads and preprocesses a dataset of arXiv papers.
- Generates dense vector embeddings for text using a SentenceTransformer model.
- Builds a FAISS index for efficient similarity search.
- Supports querying with natural language and retrieves the most relevant documents.

## Requirements

- Python 3.8+
- pandas
- scikit-learn
- sentence-transformers
- faiss
- numpy

Install dependencies:
```sh
pip install pandas scikit-learn sentence-transformers faiss-cpu numpy