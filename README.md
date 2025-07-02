# Real-Time Speech-to-Text with Noise Reduction

A real-time speech recognition system developed using Python. The system listens to the microphone input continuously, detects whether speech is present, reduces background noise, and then transcribes the voice to text using Google’s Speech Recognition API.

---

## 🧠 Developed By
**Assem Sabry** – AI Engineer  
This project is part of my research and practical development in real-time AI systems and voice interfaces.

---

## 🎯 Features

- 🎤 Real-time microphone input listening
- 🔊 Smart voice activity detection (ignores silent or low-volume input)
- 🔇 Background noise reduction using `noisereduce`
- 🧠 Google Speech Recognition API integration
- 🧱 Modular, expandable design with class-based architecture
- 🤖 Friendly feedback when no speech is detected
- 🛑 Ability to stop the assistant by voice (e.g., say "stop" or "exit")

---

## 📦 Requirements

- Python 3.8+
- Microphone device
- Internet connection (for using Google Speech API)

### 🧪 Python Packages

Install all dependencies with:

```bash
pip install -r requirements.txt
