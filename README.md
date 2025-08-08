# 🏥 KONG – Real-Time Multilingual Medical Assistant

> **Empowering seamless communication in healthcare with real-time translation and assistive technologies.**

---
Project Deployment Link - https://language-assistant-alpha.vercel.app/
---

## 📌 Problem Statement: **Multilingual Medical Translation Assistant (HC1)**

Language barriers are a major cause of **miscommunication** in healthcare. Patients often struggle to explain symptoms or understand medical advice when they don't share the same language as healthcare providers.

**KONG** bridges this gap by offering **real-time translation** for spoken, written, and signed communication — ensuring every patient’s voice is heard and understood.

---
## 📸 Screenshots

<p align="center">
  <a href="https://ibb.co/5hhcXWFd">
    <img src="https://i.ibb.co/HTTgLDd0/Screenshot-2025-08-08-081231.png" width="45%" />
  </a>
  <a href="https://ibb.co/MkBx01rY">
    <img src="https://i.ibb.co/d4mwYpFd/Screenshot-2025-08-08-081312.png" width="45%" />
  </a>
</p>

<p align="center">
  <a href="https://ibb.co/cX6YtPWY">
    <img src="https://i.ibb.co/84rY2JyY/Screenshot-2025-08-08-081328.png" width="45%" />
  </a>
  <a href="https://ibb.co/7dGThwps">
    <img src="https://i.ibb.co/DH76dxM0/Screenshot-2025-08-08-081340.png" width="45%" />
  </a>
</p>

<p align="center">
  <a href="https://ibb.co/k6yr4kRG">
    <img src="https://i.ibb.co/VpNhgr7L/Screenshot-2025-08-08-081422.png" width="45%" />
  </a>
  <a href="https://ibb.co/YB9FzGkF">
    <img src="https://i.ibb.co/ZzspnC8p/Screenshot-2025-08-08-081428.png" width="45%" />
  </a>
</p>

<p align="center">
  <a href="https://ibb.co/N60P6K7p">
    <img src="https://i.ibb.co/Z6QP6xNK/Screenshot-2025-08-08-081451.png" width="45%" />
  </a>
</p>


---

## ✨ Features

### 🔹 Core Functionality
- **🗣 Speech-to-Text Translation**  
  Real-time transcription of patient speech with **multi-language support**.
  
- **📄 Text-to-Text Medical Translation**  
  AI-powered translations that **accurately handle medical terminology** and context.
  
- **⚡ Ultra-Low Latency**  
  Seamless real-time conversation between patient and provider.

### 🔹 Bonus Functionality
- **👋 American Sign Language (ASL) to Text**  
  Converts ASL gestures (captured via webcam) into medical text.
  
- **🔊 Text-to-Speech Output**  
  Natural AI voice for translated medical content to improve understanding.
  

---

## 🛠 Tech Stack

| Layer            | Technologies |
|------------------|--------------|
| **Frontend**     | React.js, Tailwind CSS |
| **Backend**      | Node.js, Express.js |
| **Translation**  | OpenAI GPT-4, Google Translate API (Fallback) |
| **Sign Language**| Mediapipe, Custom ASL Model |
| **Speech**       | Web Speech API, Whisper, ElevenLabs (TTS) |

---

## 👥 Team KONG – *#BuiltAtCodeZilla*

| Name            | Role |
|-----------------|------|
| **Nikhil Agrawal** | Full Stack + Integration Lead |
| **Shubham Awari**  | Speech & Sign Language Dev + DevOps |
| **Archit Mishra**  | Backend + Translation Engine |
| **Parth Pareek**   | Frontend + UX Designer |

---

## 📸 Screenshots

*(Add screenshots of UI, ASL input module, speech-to-text module, etc.)*

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/nikhil-agarwal9829/language-assistant.git
cd language-assistant
2️⃣ Install Dependencies
bash
Copy
Edit
npm install
3️⃣ Run Development Server
bash
Copy
Edit
npm run dev
4️⃣ Backend Setup
Create a .env file in the backend folder with:

env
Copy
Edit
OPENAI_API_KEY=your_openai_key
GOOGLE_TRANSLATE_API_KEY=your_google_translate_key
ELEVENLABS_API_KEY=your_elevenlabs_key
Start backend:

bash
Copy
Edit
npm start

📅 Future Enhancements
📍 Location-based emergency translation for ambulances.

📊 Analytics dashboard for hospitals to track translation usage.

📱 Mobile app for offline translation in rural areas.

📜 License
This project is licensed under the MIT License – feel free to use and modify.

💙 Built with care to make healthcare accessible for everyone.

