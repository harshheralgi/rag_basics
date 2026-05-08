# RAG with PDF, Local Persist & Add Docs

A simple Retrieval-Augmented Generation (RAG) project using Python and Jupyter notebooks.

This project demonstrates:

- Basic RAG with custom text
- RAG using PDF documents
- Persistent vector storage
- Adding new documents dynamically
- Local vector database persistence

---

# Project Structure

```bash
.
├── Docs/
├── Vector/
├── 1_RAG_with_own_text.ipynb
├── 2_RAG_PDF.ipynb
├── 3_RAG_Local_Persist.ipynb
├── 4_RAG_Add_Docs.ipynb
├── main.py
├── requirements.txt
├── pyproject.toml
├── README.md
└── uv.lock
```

---

# Features

## 1. RAG with Custom Text
Notebook:
```bash
1_RAG_with_own_text.ipynb
```

- Create embeddings from raw text
- Store vectors
- Ask questions from your own content

---

## 2. RAG with PDF
Notebook:
```bash
2_RAG_PDF.ipynb
```

- Load PDF documents
- Split into chunks
- Create embeddings
- Query PDF content

---

## 3. Local Vector Persistence
Notebook:
```bash
3_RAG_Local_Persist.ipynb
```

- Persist vector database locally
- Reload vectors without recomputing embeddings

---

## 4. Add Documents Dynamically
Notebook:
```bash
4_RAG_Add_Docs.ipynb
```

- Add new documents to existing vector store
- Update knowledge base incrementally

---

# Tech Stack

- Python
- LangChain
- ChromaDB / Vector Store
- HuggingFace Embeddings
- Jupyter Notebook

---

# Installation

## Clone Repository

```bash
git clone <your-repo-url>
cd <repo-name>
```

---

## Create Virtual Environment

### Using venv

```bash
python -m venv venv
```

Activate environment:

#### Windows

```bash
venv\Scripts\activate
```

#### Mac/Linux

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Environment Variables

Create a `.env` file in the root directory.

```env
GROQ_API_KEY=your_openai_api_key
```

---

# Run Jupyter Notebook

```bash
jupyter notebook
```

Open notebooks one by one and execute cells.

---

# Usage Flow

## Step 1
Run:

```bash
1_RAG_with_own_text.ipynb
```

Learn basic RAG pipeline.

---

## Step 2
Run:

```bash
2_RAG_PDF.ipynb
```

Query PDF documents.

---

## Step 3
Run:

```bash
3_RAG_Local_Persist.ipynb
```

Persist vector database locally.

---

## Step 4
Run:

```bash
4_RAG_Add_Docs.ipynb
```

Add additional documents to existing knowledge base.

---

# Example Workflow

```text
PDF/Text Documents
        ↓
Document Loader
        ↓
Text Splitter
        ↓
Embeddings
        ↓
Vector Store
        ↓
Retriever
        ↓
LLM Response
```

---

# Requirements

Example packages used:

```txt
langchain
openai
chromadb
pypdf
jupyter
python-dotenv
tiktoken
```

---

# Future Improvements

- Streamlit UI
- Chat memory
- Multi-PDF support
- Hybrid search
- FAISS integration
- Ollama / Local LLM support
- API deployment

---

# Author

Harsh Heralgi

---
