# 🩺 AI Medical Chatbot

An AI-powered Medical Chatbot built using **Flask + LangChain + Mistral AI + Pinecone + HuggingFace Embeddings + RAG Architecture**.

The chatbot allows users to ask medical-related questions and generates context-aware responses by retrieving information from uploaded medical PDF documents.

---

## 🚀 Features

✅ AI-powered medical question answering  
✅ Retrieval-Augmented Generation (RAG)  
✅ PDF document ingestion  
✅ Semantic search using vector embeddings  
✅ Conversation history support  
✅ Pinecone vector database integration  
✅ Mistral LLM integration  
✅ Responsive chat interface  

---

# 🏗️ Architecture

```text
User
 ↓
Frontend (HTML + CSS + JS)
 ↓
Flask Backend
 ↓
LangChain Retriever
 ↓
Pinecone Vector DB
 ↓
HuggingFace Embeddings
 ↓
Mistral AI
 ↓
Response
```

---

# 🛠️ Tech Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Flask
- Python

### AI / ML
- LangChain
- Mistral AI
- HuggingFace
- Sentence Transformers

### Vector Database
- Pinecone

### Environment
- Conda

---

# 📂 Project Structure

```text
medical-chatbot
│
├── app.py
├── store_index.py
├── requirements.txt
├── .env
│
├── src/
│   ├── helper.py
│
├── Data/
│   └── medical PDFs
│
├── templates/
│   └── chat.html
│
├── static/
│   ├── style.css
│   └── script.js
│
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/himanshugithub360/AI-Medical-Chatbot.git
```

Move into project:

```bash
cd AI-Medical-Chatbot
```

---

## Create Environment

```bash
conda create -n mchatbot python=3.10 -y
```

Activate:

```bash
conda activate mchatbot
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Environment Variables

Create `.env`

```env
PINECONE_API_KEY=your_key

MISTRAL_API_KEY=your_key

FLASK_SECRET_KEY=your_secret
```

---

# 📄 Add Medical PDFs

Place PDFs inside:

```text
Data/
```

---

# 🔍 Create Vector Index

```bash
python store_index.py
```

---

# ▶️ Run Application

```bash
python app.py
```

Open:

```text
http://localhost:8080
```

---

# 💬 Example Questions

```text
What is diabetes?

What are symptoms of fever?

How can blood pressure be controlled?
```

---

# 🔐 Disclaimer

This project is for educational purposes only.

It does not replace professional medical advice, diagnosis, or treatment.

Always consult licensed healthcare professionals.

---

# 📌 Future Improvements

- User Authentication
- Voice Input
- Multi-PDF Upload
- Chat History Database
- Docker Deployment
- Cloud Deployment
- Streaming Responses

---

# 👨‍💻 Author

Himanshu Kumar

GitHub:
https://github.com/himanshugithub360
