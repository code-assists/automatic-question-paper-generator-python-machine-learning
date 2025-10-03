# 📝 Automatic Question Paper Generator Machine Learning Project | AI + RAG + FastAPI + ReactJS

**Automatic Question Paper Generator** built using **Python FastAPI, LangChain (RAG), LLMs, and ReactJS**.  
Upload a **course PDF** and instantly generate **Single Choice, Multiple Choice (MCQ), and Subjective** questions.  

This is a **full-stack solution** that integrates **semantic vector search, RAG pipelines, and LLM-powered rephrasing** to deliver **high-quality, varied, and scalable exam question papers** — perfect for **Final Year Projects (B.Tech, MCA, M.Tech, BCA)** or **educators exploring AI in EdTech**.  

---

## 🎬 Project Demo  
▶️ **YouTube Video**: (https://www.youtube.com/watch?v=5ny5-vX5kbo)  

---

## 📖 Abstract  

Manual exam paper preparation is time-consuming, repetitive, and error-prone.  
This system automates the entire process using **Retrieval-Augmented Generation (RAG)** and **LLMs**.  

Steps:  
1. **Upload PDF** → Course syllabus or study material.  
2. **Chunk & Embed** → Content split into **1000 tokens** with **200 overlap**.  
3. **Vector Search** → Retrieve most relevant text for question generation.  
4. **LLM Question Generation** → Create **MCQ, Single Choice, Subjective** questions.  
5. **Refinement** → Rephrasing, difficulty balancing, and clarity.  
6. **Export** → Download **PDF / DOCX / JSON** formatted question paper.  

This approach ensures **scalability, consistency, and automation** in **exam paper generation**.  

---

## 🛠️ Tech Stack  

- **Frontend**: ReactJS, Axios, TailwindCSS/Bootstrap  
- **Backend**: Python FastAPI, Uvicorn, Pydantic  
- **AI / RAG**: LangChain, LLMs (OpenAI/Local), FAISS/Chroma Vector DB  
- **Auth**: JWT Authentication  
- **Database / Storage**: Local DB, Object storage for PDFs  
- **Optional**: Docker, Poetry, Node.js  

---

## 🚀 Features  

- 🔒 **Secure Login** → Database Based authentication  
- 📂 **PDF Upload & Processing** → Automated chunking & vectorization  
- 🎯 **Multiple Question Types** → MCQs, Single Choice, Subjective  
- 🧠 **Semantic Vector Search** → Retrieves contextually relevant content  
- ⚡ **AI-Powered Refinement** → Clear, varied, difficulty-adjusted questions  
- 📑 **Preview & Edit** → Approve before export  
- 📤 **Export Options** → PDF
- 📜 **History** → Track previously generated papers  

---

## 📂 Project Modules  

- **Authentication Module** → User registration, login, JWT tokens  
- **PDF Manager** → Upload, list, delete PDFs  
- **Indexer** → Chunk & embed course content  
- **Generator** → Question creation (MCQs, Subjective, Single Choice)  
- **Refiner** → Improve clarity, difficulty balance  
- **Paper Builder** → Shuffle, format, and export  
- **Admin Panel (Optional)** → Manage users & files  

---
