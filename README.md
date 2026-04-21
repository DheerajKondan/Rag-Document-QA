# 📄 RAG Document Q&A System

An AI-powered application that allows users to upload PDF documents and ask questions.  
This project uses **Retrieval-Augmented Generation (RAG)** to fetch relevant content from the document and generate accurate answers using a language model.

---

## 🚀 Features

- 📂 Upload PDF documents
- ✂️ Smart text chunking
- 🔍 Semantic search using FAISS
- 🧠 Embeddings with Sentence Transformers
- 🤖 Answer generation using FLAN-T5
- 🌐 Interactive UI using Streamlit

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Frontend:** Streamlit  
- **Embedding Model:** SentenceTransformers (`all-MiniLM-L6-v2`)  
- **Vector Database:** FAISS  
- **LLM:** FLAN-T5 (Hugging Face Transformers)  
- **PDF Processing:** PyPDF  

---

## 📁 Project Structure



---

## ⚙️ How It Works

1. Upload a PDF  
2. Extract text using PyPDF  
3. Split text into chunks  
4. Convert chunks into embeddings  
5. Store embeddings in FAISS  
6. User asks a question  
7. Retrieve top relevant chunks  
8. Send context + question to LLM  
9. Generate final answer  

---

## ▶️ Run Locally

### 1️⃣ Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/Rag-Document-QA.git
cd Rag-Document-QA

python -m venv venv
venv\Scripts\activate   # Windows

pip install -r requirements.txt

streamlit run app.py

