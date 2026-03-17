# 🔍 RAG Pipeline from Scratch (MiniLM + FAISS + Gemini)

This project demonstrates a complete **Retrieval-Augmented Generation (RAG)** pipeline built from scratch to understand how each component works under the hood.

Instead of relying on frameworks, this implementation focuses on the **core building blocks of RAG systems**.

---

## 🚀 What This Project Does

- Loads documents from multiple formats (TXT, CSV, DOCX)
- Cleans and preprocesses text
- Splits documents into meaningful chunks
- Converts text into embeddings using MiniLM
- Stores embeddings in vector databases (FAISS & ChromaDB)
- Performs semantic search with filtering and scoring
- Generates answers using retrieved context

---

## 🛠️ Tech Stack

- Python  
- Sentence Transformers (`all-MiniLM-L6-v2`)  
- FAISS (Vector Search)  
- ChromaDB (Vector Store)  
- Gemini API (LLM)  
- NLTK (Text Processing)  

---

## 📊 Demo Output

### 🔹 Query: Work-from-home policy

---

## 💡 Key Learnings

- RAG is not just about the LLM — retrieval quality is critical  
- Chunking strategy significantly impacts accuracy  
- Vector similarity alone is not enough — filtering improves results  
- Proper prompt design reduces hallucinations  

---

## ⚙️ How to Run

```bash
pip install -r requirements.txt

RAG_pipeline.ipynb

