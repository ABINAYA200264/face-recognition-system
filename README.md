# face-recognition-system


![image](https://github.com/user-attachments/assets/309ec44b-97fd-48e0-9aa3-1e2c5ad1200f)


# 🧠 Face Recognition + RAG-based Chat System

A full-stack AI system that performs real-time face registration and recognition, and answers chat-based queries using a Retrieval-Augmented Generation (RAG) engine.

---

## 📦 Project Structure
face-recognition-system/
├── frontend/ # React.js frontend (camera, chat)
├── backend/ # Node.js API backend
├── face-engine/ # Python face recognition and RAG engine
│ ├── recognizer.py
│ ├── encodings.pkl
│ └── rag_engine/
│ ├── query_handler.py
│ └── faiss_index/
│ └── index.faiss
├── .env # API keys and config
└── README.md


---

## 🚀 Features

✅ Face Registration with camera  
✅ Real-time Face Recognition  
✅ WebSocket-based Chat Interface  
✅ RAG Engine using LangChain + FAISS  
✅ Vector-based similarity + LLM-based responses  
✅ Logs all backend activity  

---

## 🛠️ Technologies Used

| Layer             | Stack                                |
|------------------|---------------------------------------|
| Frontend         | React.js, Axios, WebcamJS             |
| Backend          | Node.js, Express.js, Socket.IO        |
| Face Recognition | Python, `face_recognition`, pickle    |
| RAG Engine       | LangChain, FAISS, OpenAI GPT          |
| Database         | Local FS (Pickle), FAISS Vector Index |

---

## ⚙️ Setup Instructions

### 🔧 1. Clone the Repo

```bash
git clone https://github.com/your-username/face-recognition-rag-chat.git
cd face-recognition-rag-chat

https://katomaran.com


