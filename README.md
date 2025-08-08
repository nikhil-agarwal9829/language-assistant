# 🏥 KONG – Real-Time Multilingual Medical Assistant

> **Empowering seamless communication in healthcare with real-time translation and assistive technologies.**

---

## 📌 Problem Statement: **Multilingual Medical Translation Assistant (HC1)**

Language barriers are a major cause of **miscommunication** in healthcare. Patients often struggle to explain symptoms or understand medical advice when they don't share the same language as healthcare providers.

**KONG** bridges this gap by offering **real-time translation** for spoken, written, and signed communication — ensuring every patient’s voice is heard and understood.

---
## 📸 Screenshots

| Home Page | Translation Interface |
|-----------|-----------------------|
| ![Home](https://i.ibb.co/N60P6K7/home.png) | ![Translation](https://i.ibb.co/YB9FzGkF/translation.png) |

| ASL Recognition | ASL to Text Output |
|-----------------|--------------------|
| ![ASL Input](https://i.ibb.co/k6yr4kRG/asl-input.png) | ![ASL Output](https://i.ibb.co/7dGThwp/asl-output.png) |

| Speech-to-Text Module | Text-to-Speech Module |
|-----------------------|-----------------------|
| ![Speech-to-Text](https://i.ibb.co/cX6YtPW/speech-to-text.png) | ![Text-to-Speech](https://i.ibb.co/MkBx01r/text-to-speech.png) |

| Multi-Language Support |
|------------------------|
| ![Multi-Language](https://i.ibb.co/5hhcXWF/multi-language.png) |
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

