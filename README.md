# Jarvis 2.0 – Modular Desktop AI Assistant

## 🚀 Overview
Jarvis 2.0 is a modular Python-based Desktop AI Assistant capable of executing voice commands, automating system tasks, and maintaining conversational memory.

This project focuses on clean architecture, modular design, and practical AI system structuring.

---

## 🧠 Features
- Voice recognition
- Text-to-speech responses
- Modular architecture (Brain, Ear, Mouth, Actions)
- Short-term memory using deque
- Long-term memory using JSON
- Desktop automation
- Web interaction support

---

## 🏗️ Architecture
- `brain.py` – Core logic & memory management  
- `ear.py` – Voice input processing  
- `mouth.py` – Text-to-speech output  
- `actions.py` – System command execution  
- `memory.json` – Long-term memory storage  

---

## 🛠️ Technologies Used
- Python  
- SpeechRecognition  
- pyttsx3  
- JSON  
- OS & Webbrowser modules
