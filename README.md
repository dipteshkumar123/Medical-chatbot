# 🧠 AI Medical Assistant Chatbot (Voice + Web + PDF Report)

This project is a smart AI-powered medical chatbot that helps users report health symptoms using voice or text. It responds with friendly and helpful medical advice, tracks symptom history, and generates downloadable health reports with charts.

---

## 🧩 Components Used

- 🧠 **Natural Language Processing (NLP)** for symptom detection  
- 🎤 **Speech Recognition** for Speech-to-Text (STT) using `speech_recognition`  
- 🔈 **Text-to-Speech (TTS)** using `edge-tts`  
- 🤖 **Groq API** with `LLaMA3-8B` model for generating AI responses  
- 📊 **Matplotlib** for plotting symptom severity charts  
- 📄 **ReportLab** for PDF health report generation  
- 🌐 **Flask + HTML + JavaScript** for modern web interface  

---

## ✨ Features

- 🧠 Detects symptoms using NLP from voice/text input  
- 📈 Tracks and logs symptom severity  
- 📄 Generates AI-powered health reports in PDF format  
- 🎤 Voice-based CLI interface with STT + TTS  
- 🌐 Clean web UI built with Flask + JavaScript  
- 🧠 Uses **Groq API** for friendly AI-based medical responses  
- 🗂 Logs every user interaction in `symptom_memory.txt`

---

## 🛠 Methodology

1. Accept user input (via voice or text)  
2. Detect symptoms and ask severity (CLI only)  
3. Generate AI reply via **Groq API (LLaMA3-8B model)**  
4. Store logs and update symptom memory  
5. Visualize symptom severity using bar chart  
6. Create downloadable PDF health report  
