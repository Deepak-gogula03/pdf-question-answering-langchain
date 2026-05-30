PDF Question Answering using LangChain
Overview

This project demonstrates how to build a PDF Question Answering system using LangChain, OpenAI Embeddings, and FAISS Vector Database.

The application:

Reads a PDF document
Extracts text from the document
Splits text into chunks
Generates embeddings using OpenAI
Stores embeddings in FAISS
Retrieves relevant chunks based on user queries
Uses an LLM to answer questions from the document

Problem Statement

Large PDF documents can be difficult to search manually.

This project uses Retrieval-Augmented Generation (RAG) to enable natural language question answering over PDF files.

Tech Stack
Python
LangChain
OpenAI
FAISS
PyPDF2
Jupyter Notebook

