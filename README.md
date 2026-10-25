# PDF Chatbot using RAG and Ollama

## Overview
This project allows users to ask questions about PDF documents using Retrieval-Augmented Generation (RAG). It loads a PDF splits the text into chunks, retrieves relevant information using vector embeddings and generates answers using a language model through Ollama.

## Technologies Used
- Python
- Jupyter Notebook
- LangChain
- Ollama
- ChromaDB
- Hugging Face Embeddings
- IPyWidgets
- PyPDF

## Features
- Load PDF documents
- Extract text from PDF pages
- Split documents into smaller chunks
- Generate embeddings using Hugging Face
- Store and retrieve relevant chunks using Chroma
- Answer questions using an Ollama language model
- Interact with the notebook using IPyWidgets

## Project Workflow
1. Load the PDF document.
2. Split the document into text chunks.
3. Generate embeddings for the chunks.
4. Store embeddings in ChromaDB.
5. Retrieve relevant chunks based on the user's question.
6. Generate an answer using the Ollama language model.

## Installation

### 1. Clone the Repository
```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd YOUR_REPOSITORY_NAME
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Install Ollama
Download and install Ollama from:
https://ollama.com/

Pull the same model used in your notebook:
```bash
ollama pull YOUR_MODEL_NAME
```

### 4. Run the Notebook
Open the notebook in Jupyter and execute the cells in order.

## Requirements
Python, the packages listed in `requirements.txt`, Ollama and the language model used by the notebook.

## Learning Outcomes
- Understanding Retrieval-Augmented Generation (RAG)
- Working with document loaders and text splitters
- Using embeddings and vector databases
- Building a PDF question-answering pipeline with LangChain

## Future Improvements
- Support multiple PDF documents
- Improve answer quality and retrieval accuracy
- Build a user-friendly web interface

## Author
Pravash
