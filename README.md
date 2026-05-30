# 📄 PDF Question Answering using LangChain & OpenAI

Welcome to the **PDF Question Answering System**! This project demonstrates how to build a Retrieval-Augmented Generation (RAG) application that allows users to ask questions from PDF documents and receive intelligent answers using OpenAI and LangChain.

---

## 🚀 Overview

Large PDF documents can be difficult to search and analyze manually. This project solves that problem by converting PDF content into vector embeddings and retrieving the most relevant information based on user queries.

The application uses:

* **PyPDF2** for PDF text extraction
* **LangChain** for orchestration
* **OpenAI Embeddings** for vector generation
* **FAISS** for vector storage and similarity search
* **OpenAI LLM** for answer generation

---

## 📌 Features

### 📖 PDF Text Extraction

* Read and process PDF documents
* Extract text from multiple pages

### ✂️ Text Chunking

* Split large documents into smaller chunks
* Improve retrieval performance and accuracy

### 🧠 Embedding Generation

* Generate vector embeddings using OpenAI Embeddings
* Convert textual information into searchable vectors

### 🗄️ FAISS Vector Database

* Store document embeddings efficiently
* Perform fast similarity searches

### 🔍 Semantic Search

* Retrieve the most relevant document chunks
* Context-aware information retrieval

### 💬 Question Answering

* Ask questions in natural language
* Generate accurate answers from PDF content

---

## 🏗️ Project Architecture

```text
PDF Document
      │
      ▼
Text Extraction
      │
      ▼
Text Chunking
      │
      ▼
OpenAI Embeddings
      │
      ▼
FAISS Vector Store
      │
      ▼
Similarity Search
      │
      ▼
Relevant Context Retrieval
      │
      ▼
OpenAI Language Model
      │
      ▼
Generated Answer
```

---

## 🛠️ Technologies Used

* Python
* LangChain
* OpenAI
* FAISS
* PyPDF2
* Jupyter Notebook

---

## 📋 Prerequisites

Before running this project, ensure you have:

* Python 3.9 or above
* Jupyter Notebook
* OpenAI API Key

Install the required packages:

```bash
pip install langchain
pip install langchain-openai
pip install langchain-community
pip install faiss-cpu
pip install PyPDF2
pip install python-dotenv
```

Or install from requirements.txt:

```bash
pip install -r requirements.txt
```

---

## ⚙️ Environment Setup

Create a `.env` file in the root directory:

```env
OPENAI_API_KEY=YOUR_OPENAI_API_KEY
```

Never upload your API keys to GitHub.

Add `.env` to `.gitignore`:

```gitignore
.env
```

---

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/pdf-question-answering-langchain.git
```

Move into the project directory:

```bash
cd pdf-question-answering-langchain
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
PDFQueryLangChain.ipynb
```

---

## ▶️ Usage

### Step 1

Run all notebook cells.

### Step 2

Load the PDF document.

### Step 3

Extract text from the PDF.

### Step 4

Split the extracted text into chunks.

### Step 5

Generate embeddings and store them in FAISS.

### Step 6

Enter your question.

### Step 7

Retrieve relevant document chunks.

### Step 8

Generate answers using OpenAI.

---

## 💡 Example Questions

```text
What is Attention Is All You Need?
```

```text
Who are the authors of the paper?
```

```text
What is Multi-Head Attention?
```

```text
Explain the Transformer Architecture.
```

```text
What are the key contributions of this research paper?
```

---

## 🎯 Learning Outcomes

This project helped in understanding:

* Retrieval-Augmented Generation (RAG)
* LangChain Framework
* OpenAI API Integration
* Vector Databases
* FAISS
* Embeddings
* Semantic Search
* Document Question Answering Systems

---

## 🔮 Future Enhancements

* Streamlit User Interface
* Multiple PDF Support
* Chat History
* Conversational Memory
* ChromaDB Integration
* Local LLM Support
* Source Citations
* PDF Upload Interface
