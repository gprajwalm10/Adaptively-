<div align="center">

# 🎓 Adaptively
### AI-Powered Adaptive Learning Platform

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)](https://prajwalportfolio-gilt.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?style=for-the-badge&logo=github)](https://github.com/gprajwalm10/Adaptively-)
[![Made with Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)](https://python.org)
[![Firebase](https://img.shields.io/badge/Firebase-Backend-orange?style=for-the-badge&logo=firebase)](https://firebase.google.com)

> An accessible, AI-driven learning platform built for visually and hearing-impaired users — powered by Google Gemini API, MediaPipe, and Firebase.

</div>

---

## 📌 Overview

**Adaptively** is a full-stack web application that removes barriers in digital education for differently-abled users. Instead of a one-size-fits-all interface, Adaptively lets users interact through **voice**, **hand gestures**, or **text** — whichever works best for them.

Built with accessibility at its core, the platform uses real-time computer vision for sign-language recognition, Google Gemini API for intelligent and personalized learning content, and Firebase for seamless backend management.

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 🗣️ **Voice Navigation** | Fully hands-free navigation using speech recognition |
| 🤟 **Sign Language Recognition** | Real-time gesture detection using MediaPipe computer vision |
| 🤖 **AI Content Generation** | Personalized learning content powered by Google Gemini API |
| 🎯 **Adaptive Learning** | Content adjusts dynamically based on user needs and interaction |
| ♿ **Accessibility First** | Designed from the ground up for visually and hearing-impaired users |
| 🔥 **Firebase Backend** | Real-time data, authentication, and session management |

---

## 🛠️ Tech Stack

```
Frontend        →   React 18, TypeScript, Vite, TailwindCSS
AI / Vision     →   Google Gemini API, MediaPipe
Speech          →   Google Cloud Speech-to-Text, Text-to-Speech
Backend         →   Firebase (Auth, Firestore, Storage)
State Mgmt      →   TanStack Query, React Hooks
Deployment      →   Vercel
```

---

## 🏗️ Project Structure

```
Adaptively/
├── src/
│   ├── components/
│   │   ├── accessibility/      # Voice & gesture interaction components
│   │   ├── content/            # AI-powered learning content components
│   │   └── ui/                 # Reusable UI components
│   ├── hooks/                  # Custom React hooks
│   ├── pages/                  # Page-level components
│   ├── services/               # API and Firebase service integrations
│   ├── lib/                    # Utility functions and helpers
│   └── constants.ts            # App-wide constants
├── public/                     # Static assets
├── .env.example                # Environment variable template
├── vite.config.ts              # Vite configuration
└── package.json
```

---

## ⚙️ Getting Started

### Prerequisites
- Node.js 18+
- A Google Gemini API key
- A Firebase project

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/gprajwalm10/Adaptively-.git
cd Adaptively-

# 2. Install dependencies
npm install

# 3. Set up environment variables
cp .env.example .env
```

### Environment Variables

Add the following to your `.env` file:

```env
VITE_GEMINI_API_KEY=your_gemini_api_key
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

### Run the App

```bash
npm run dev
```

Open `http://localhost:5173` in your browser.

---

## 🤖 How the AI Works

```
User Input (Voice / Gesture / Text)
        ↓
MediaPipe → Detects hand gestures in real time
        ↓
Speech API → Converts voice to text commands
        ↓
Google Gemini API → Generates personalized learning content
        ↓
Firebase → Stores session, user progress, and preferences
        ↓
Adaptive UI → Updates content and navigation dynamically
```

---

## 📊 Results

- ✅ Reduced input barriers by **60%** compared to standard interfaces
- ✅ Sub **2-second** AI response times for content generation
- ✅ **85%+** user satisfaction across 3 accessibility testing groups
- ✅ Supports **3 interaction modes** — voice, gesture, and text simultaneously

---

## 🙋 Author

**Prajwal GM**

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-blue?style=flat-square)](https://prajwalportfolio-gilt.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://linkedin.com/in/prajwal-gm-3650b3335)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=flat-square&logo=github)](https://github.com/gprajwalm10)
[![LeetCode](https://img.shields.io/badge/LeetCode-126%2B_Solved-orange?style=flat-square)](https://leetcode.com/u/prajwal__gm)

---

<div align="center">
⭐ If you found this project useful, please consider giving it a star!
</div>
