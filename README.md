# AI Flow Builder

A full-stack MERN application where users can enter a prompt, generate an AI response, and visualize the flow using React Flow.

---

## 🚀 Tech Stack

- React (Vite)
- React Flow
- Node.js + Express
- MongoDB
- OpenRouter API

---

## ⚙️ Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/mhw3011/ai-flow-builder.git
cd ai-flow-builder
```

---

### 2. Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside `backend/`:

```env
OPENROUTER_API_KEY=your_api_key
MONGO_URI=your_mongodb_uri
```

Run backend:

```bash
node server.js
```

---

### 3. Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 🧠 Usage

- Enter a prompt in the input node
- Click **Run Flow** to generate AI response
- Click **Save** to store it in MongoDB

---

## 🔐 Note

API keys are stored securely in environment variables and are not exposed to the frontend.
