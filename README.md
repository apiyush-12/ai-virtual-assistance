# 🤖 AI Voice Assistant

A full-stack AI-powered voice assistant that understands voice commands, processes them using AI, and performs real-time actions like searching, opening apps, and answering questions.

---

## 🚀 Live Demo

* 🌐 Frontend: https://virtual-assistance-9ypu.onrender.com
* ⚙ Backend: https://virtual-assistance-backend-s3m9.onrender.com

---

## ✨ Features

* 🎤 **Voice Recognition** – Interact using your voice
* 🤖 **AI-Powered Responses** – Integrated with Gemini API
* 🔊 **Text-to-Speech** – Assistant responds with voice output
* 🌐 **Smart Commands Execution**

  * Google Search
  * YouTube Search / Play
  * Open Instagram
  * Weather Info
  * Calculator Access
* 🧠 **General Knowledge Mode** – Answers questions directly
* ⚡ **Real-Time Processing**
* 🔐 **User Authentication System**

---

## 🛠 Tech Stack

### Frontend

* React.js
* Vite
* Axios
* Web Speech API (Speech Recognition + Speech Synthesis)

### Backend

* Node.js
* Express.js
* MongoDB
* Gemini API (Google AI)

### Deployment

* Frontend → Vercel
* Backend → Render

---

## 📂 Project Structure

```
virtual-assistant/
│
├── frontend/
│   ├── src/
│   ├── components/
│   └── pages/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   └── config/
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/virtual-assistant.git
cd virtual-assistant
```

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create `.env` file:

```env
PORT=8000
MONGO_URI=your_mongodb_connection
GEMINI_API_URL=your_gemini_api_url
```

Run backend:

```bash
npm run dev
```

---

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 🎯 Usage

1. Open the application
2. Speak your assistant name (e.g., *"Jarvis"*)
3. Give a command

### Example Commands:

* "Jarvis open YouTube"
* "Jarvis search AI on Google"
* "Jarvis what is machine learning"
* "Jarvis what time is it"

---

## ⚠️ Known Challenges

* API rate limiting (Gemini free tier)
* Speech recognition interruptions (handled with restart logic)
* Network latency in real-time voice processing

---

## 🔮 Future Improvements

* 🎯 Wake word detection ("Hey Jarvis")
* 🧠 Conversation memory (context awareness)
* 🔄 Multi-AI fallback system
* 📱 Mobile optimization
* 🎨 Advanced UI animations

---

## 👨‍💻 Author

**Piyush Kumar**

* B.Tech (Computer Networking)
* Passionate about AI, Cybersecurity & Full-Stack Development
