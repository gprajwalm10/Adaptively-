# Adaptively — AI-Powered Adaptive Learning Platform

An accessible, AI-driven learning platform built for visually and hearing-impaired users. Adaptively combines voice navigation, sign-language recognition, and personalized AI content generation to remove barriers in digital education.

## What It Does

- **Voice Navigation** — hands-free interaction using Google Cloud Speech-to-Text, enabling users to navigate the platform entirely by voice
- **Sign Language Recognition** — real-time gesture detection using MediaPipe computer vision for hearing-impaired users
- **AI Content Generation** — personalized learning content powered by Google Gemini API, adapting to each user's level and needs
- **Multimodal Interaction** — supports voice, gesture, and text input simultaneously

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React 18, TypeScript, Vite, TailwindCSS |
| AI / ML | Google Gemini API, MediaPipe |
| Speech | Google Cloud Speech-to-Text, Text-to-Speech |
| Backend | Firebase (auth, database, storage) |
| State | TanStack Query, React Hooks |

## Getting Started

```bash
# Clone the repo
git clone https://github.com/gprajwalm10/Adaptively-.git
cd Adaptively-

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Add your API keys to .env

# Start the development server
npm run dev
```

## Project Structure
