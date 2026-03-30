# 🧠 AI Assistant Chatbot (RAG System)

A production-style AI chatbot built using **Retrieval-Augmented Generation (RAG)** and **LLM orchestration**, designed to deliver context-aware, multi-personality conversations with real-time document understanding.

---

## 🚀 Overview

This project implements an intelligent AI assistant capable of:

- Switching between multiple conversational personalities
- Understanding and responding based on uploaded documents (PDFs)
- Generating context-aware responses using retrieval + reasoning pipelines
- Maintaining conversational memory for coherent interactions

Unlike basic chatbots, this system leverages **RAG architecture** to combine **vector search + LLM reasoning**, enabling more accurate and grounded responses.

---

## 🔥 Core Features

### 🤖 Multi-Personality System
Dynamically adapts tone and behavior across roles:
- 🎓 Professor (analytical, strict)
- 🎯 Career Counselor (structured, guidance-focused)
- 🧑‍🤝‍🧑 Best Friend (casual, friendly)
- 💖 Partner (empathetic, emotional)
- 👨‍👩‍👧 Family Member (supportive, caring)

---

### 📄 Document-Aware Chat (RAG)
- Upload PDFs and interact with their content
- Extracts text using **PyMuPDF**
- Generates embeddings and performs **semantic retrieval**
- Uses retrieved context for accurate answer generation

---

### 🧠 Context-Aware Responses
- Maintains session-level conversational memory
- Improves continuity and avoids repetitive responses

---

### 🌐 Multilingual Support
- Supports both **English + Hindi**
- Dynamically adapts responses based on user input

---

### 📥 Chat Export
- Download complete chat history for future reference

---

## 🏗️ System Architecture

User Input
↓
Personality Layer (Prompt Engineering)
↓
Retriever (FAISS / Embeddings)
↓
Context Injection
↓
LLM (Gemini API)
↓
Response Generation

---

## ⚙️ Tech Stack

### 🧠 AI & LLM
- Google Gemini API  
- Prompt Engineering  
- RAG Pipeline (Retrieval + Generation)

### 📚 Data Processing
- PyMuPDF (PDF parsing)
- Embeddings (for semantic search)

### 🖥️ Backend & UI
- Streamlit (interactive UI)

---

## 🔐 Security

- API keys are securely managed using **Streamlit secrets**
- No sensitive data is exposed in the codebase

---

## 🧪 Key Capabilities

- Context-aware question answering  
- Personality-driven response generation  
- Document-based reasoning  
- Real-time conversational interaction  

---

## 🚀 How to Run Locally

### 1. Clone the repository

git clone https://github.com/GAURAV0440/your-repo-name.git
cd your-repo-name

### 2. Install dependencies
pip install -r requirements.txt
### 3. Add API Key

Create a .streamlit/secrets.toml file:

GEMINI_API_KEY = "your_api_key_here"
### 4. Run the app
streamlit run app.py

### 📌 Future Improvements
1. Vector database integration (FAISS → scalable DB)
2. Agent-based task execution
3. Memory persistence across sessions
4. Voice-based interaction
5. Advanced evaluation pipeline (LLM scoring)

### 💡 What Makes This Project Strong
1. Goes beyond basic chatbot → implements RAG architecture
2. Demonstrates LLM orchestration + prompt design
3. Combines retrieval + reasoning + UI integration
4. Shows real-world AI system design thinking

## ❤️ Acknowledgment

Built with a focus on creating intelligent, human-like AI interactions using modern LLM systems.
