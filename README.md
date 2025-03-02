# 📄 Smart Document Search & Q&A Bot

An AI-powered **Smart Document Search & Q&A Bot** that allows users to **upload PDFs, extract text, store documents as vector embeddings, and retrieve AI-powered answers** based on user queries. This system enhances document search efficiency with **text summarization and intelligent Q&A capabilities**.

---

## 🚀 Features
✅ **Upload & Extract**: Users can upload PDFs, and the system extracts text efficiently.  
✅ **Vector Search**: Stores document embeddings in **ChromaDB** for fast retrieval.  
✅ **AI-Powered Q&A**: Ask questions about the uploaded documents and get relevant answers.  
✅ **Summarization**: The bot can summarize key information from documents.  
✅ **Fast & Scalable**: Built using FastAPI, ensuring speed and scalability.  
✅ **CORS Enabled**: Seamless frontend interaction.

---

## 🛠️ Tech Stack & Libraries Used

🔹 **Backend**: FastAPI (Python)  
🔹 **Vector Database**: ChromaDB (Persistent Storage)  
🔹 **Text Embeddings**: Sentence Transformers (`all-MiniLM-L6-v2`)  
🔹 **Summarization Model**: T5-small (Hugging Face Transformers)  
🔹 **PDF Processing**: PyMuPDF (fitz)  
🔹 **CORS Support**: Enabled for frontend communication  

---

## 🚀 Installation & Setup

1️⃣ **Clone the Repository**
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/Smart-Document-Search.git
cd Smart-Document-Search
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
Open your browser and visit: http://127.0.0.1:8000/docs for API documentation.
