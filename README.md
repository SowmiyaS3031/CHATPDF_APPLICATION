# CHATPDF_APPLICATION
# 📄 ChatPDF — AI Powered Document Assistant

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![LangChain](https://img.shields.io/badge/LangChain-RAG-green)
![ChromaDB](https://img.shields.io/badge/Vector%20Database-ChromaDB-orange)
![Groq](https://img.shields.io/badge/LLM-Groq%20Llama-purple)

## 🚀 Overview

**ChatPDF** is an AI-powered document question-answering application that allows users to interact with their PDF documents through natural language conversations.

Instead of manually searching through long documents, users can upload a PDF and ask questions. The application retrieves relevant information from the document and generates accurate responses using Large Language Models.

This project implements a **Retrieval-Augmented Generation (RAG)** pipeline using **LangChain, ChromaDB, and Groq LLM**.

---

## ✨ Features

✅ Upload PDF documents  
✅ Extract and process PDF content  
✅ Intelligent text chunking  
✅ Semantic search using vector database  
✅ Ask questions in natural language  
✅ AI-generated answers from document context  
✅ Page number references for sources  
✅ Fast response generation using Groq Llama model  
✅ Simple and interactive Streamlit interface  

---

## 🧠 How ChatPDF Works (RAG Pipeline)

```
              User
               |
               ↓
        Upload PDF Document
               |
               ↓
        Extract Text (PyPDF)
               |
               ↓
      Split Text into Chunks
      (LangChain Splitter)
               |
               ↓
     Store Vectors in ChromaDB
               |
               ↓
        User asks Question
               |
               ↓
    Retrieve Relevant Context
               |
               ↓
       Groq LLM Generates Answer
               |
               ↓
            Response
```

---

## 🛠️ Tech Stack

### Programming Language
- 🐍 Python

### Frontend
- Streamlit

### AI / LLM
- Groq API
- Llama 3.3 70B Versatile Model

### RAG Framework
- LangChain

### Vector Database
- ChromaDB

### PDF Processing
- PyPDF

### Environment Management
- python-dotenv

---

## 📂 Project Structure

```
CHATPDF_APPLICATION
│
├── app.py                 # Main Streamlit application
│
├── requirements.txt       # Python dependencies
│
├── README.md              # Project documentation
│
├── .gitignore             # Ignored files
│
└── .env                   # API configuration (Not uploaded)
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/SowmiyaS3031/CHATPDF_APPLICATION.git
```

### 2. Move into Project Directory

```bash
cd CHATPDF_APPLICATION
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Add Environment Variables

Create a `.env` file:

```env
GROQ_API_KEY=your_groq_api_key
```

### 5. Run the Application

```bash
streamlit run app.py
```

The application will open in your browser.

---

## 📸 Application Screenshots

Add screenshots of:

- PDF Upload Interface
- Chat Interface
- AI Generated Response

---

## 🔮 Future Enhancements

🚀 Multiple PDF conversation support  
🚀 Chat history storage  
🚀 PDF summarization feature  
🚀 Voice-based document interaction  
🚀 User authentication  
🚀 Cloud deployment  
🚀 Support for multiple file formats (DOCX, TXT, PPT)

---

## 🎯 Learning Outcomes

Through this project, I explored:

- Retrieval-Augmented Generation (RAG)
- Vector databases
- Large Language Models
- Prompt-based AI applications
- Document processing pipelines
- Building AI applications using Python

---

## 👩‍💻 Author

**Sowmiya S**

Computer Science Engineering Student

---

## 📜 License

This project is created for educational and learning purposes.
