# rag-pdf-chatbot
PDF based AI chatbot using RAG
# 📄 RAG PDF Chatbot

## 🚀 Project Description
This is a Retrieval-Augmented Generation (RAG) based AI chatbot that allows users to upload PDF files and ask questions based on the content of the document. The system extracts text from PDFs, converts it into embeddings, and uses similarity search to generate accurate answers.

## 🧠 Features
- Upload PDF documents
- Extract text from PDF
- Split text into chunks
- Generate embeddings using OpenAI
- Semantic search using FAISS
- Ask questions and get AI-generated answers

## 🛠️ Tech Stack
- Python
- Streamlit
- LangChain
- OpenAI API
- FAISS Vector Database
- PyPDF2

## ⚙️ How It Works
1. User uploads PDF
2. Text is extracted from PDF
3. Text is split into chunks
4. Embeddings are created
5. FAISS stores embeddings
6. User asks a question
7. Most relevant chunks are retrieved
8. AI generates final answer

## ▶️ How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
