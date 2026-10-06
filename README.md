# ✈️ AI Travel Guide Application

An AI-powered travel guide that provides users with informative and engaging descriptions of tourist destinations and converts the generated information into natural-sounding audio.

The application uses **Google Gemini** to generate AI-based travel descriptions and **Murf AI** to convert those descriptions into speech, allowing users to explore destinations through both text and audio.

---

## 🌐 Live Demo

🔗 **Live Application:**  
https://ai-travel-guide-application-1.onrender.com

🔗 **GitHub Repository:**  
https://github.com/muramneelima-2007/AI-Travel-Guide-Application

---

## 📌 Project Overview

The AI Travel Guide Application is designed to provide users with an interactive way to learn about tourist destinations.

Users can enter a destination, select the type of information they want, choose a language, and generate an AI-powered travel guide.

The generated description is then converted into speech using Murf AI, allowing users to listen to the travel information as an audio guide.

---

## ✨ Features

- 🤖 AI-generated travel descriptions
- 🏛️ Historical and cultural information about destinations
- 📝 Summary and Detailed explanation modes
- 🌍 Multi-language support
- 🔊 AI-powered text-to-speech
- 🎧 Audio guide generation
- ⚡ Real-time interaction between frontend and backend
- 🔐 API keys securely stored using environment variables
- 🌐 Deployed frontend and backend
- 📱 Responsive and user-friendly interface

---

## 🛠️ Technologies Used

### Frontend

- HTML5
- CSS3
- JavaScript
- Fetch API

### Backend

- Python
- Flask
- Flask-CORS
- Requests

### AI & APIs

- Google Gemini API
- Murf AI Text-to-Speech API

### Deployment

- GitHub
- Render

---

## 🏗️ System Architecture

```text
                ┌──────────────────────┐
                │       User           │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │   Frontend           │
                │ HTML + CSS + JS      │
                └──────────┬───────────┘
                           │
                           │ HTTP POST
                           ▼
                ┌──────────────────────┐
                │ Flask Backend        │
                │      Python          │
                └──────────┬───────────┘
                           │
                  ┌────────┴─────────┐
                  │                  │
                  ▼                  ▼
        ┌──────────────────┐  ┌──────────────────┐
        │   Google Gemini  │  │     Murf AI      │
        │ AI Description   │  │ Text-to-Speech   │
        └────────┬─────────┘  └────────┬─────────┘
                 │                     │
                 └──────────┬──────────┘
                            ▼
                  ┌──────────────────┐
                  │ Generated Result │
                  │ Text + Audio     │
                  └──────────────────┘