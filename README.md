 Chatbot
A **Multimodal AI Chatbot** built with RAG (Retrieval-Augmented Generation) that supports text and document-based interactions.
---
Check it out: https://chatbot-delta-five-35.vercel.app/
 Features

 AI-powered chat
 PDF & YouTube content processing
 RAG-based knowledge retrieval
 Fast Next.js + FastAPI architecture



Tech Stack 

* Frontend: Next.js, Tailwind CSS
* Backend: FastAPI
* AI: OpenAI / Groq
* Vector DB: Pinecone


Setup

Backend

```bash
cd backend
pip install -r requirements.txt
uvicorn app:app --reload

```
Frontend

```bash
cd frontend
npm install
npm run dev
```

---

Environment Variables

**Backend**

```
OPENAI_API_KEY=
GROQ_API_KEY=
PINECONE_API_KEY=
```

**Frontend**

```
NEXT_PUBLIC_API_URL=http://localhost:8000
```

---

 Deployment

* Frontend → Vercel
* Backend → Render

---


