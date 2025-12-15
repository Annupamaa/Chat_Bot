# 🤖 Chat_Bot

An **AI-powered chatbot** built with **OpenAI**, **Qdrant**, and **React** for context-aware, semantic search–based conversations.

---

## 🚀 Features

* AI chat using OpenAI
* Semantic search with Qdrant
* Fast React frontend
* Environment-based config

---

## 🛠️ Tech Stack

* **Frontend:** React
* **Backend:** Node.js (Express)
* **AI:** OpenAI API
* **Vector DB:** Qdrant

---

## ⚙️ Setup

### Backend

```bash
cd server
npm install
npm start
```

`.env`

```env
OPENAI_API_KEY=your_key
QDRANT_URL=http://localhost:6333
```

### Qdrant

```bash
docker run -p 6333:6333 qdrant/qdrant
```

### Frontend

```bash
cd client
npm install
npm start
```

