
# 🧠 AI Virtual Assistant with Gesture & Eye Detection

### 👋 Overview

This project is an **AI-powered virtual assistant** that uses **hand gestures** and **eye detection** to interact with your system. It combines **computer vision**, **speech synthesis**, and **automation** to create a futuristic hands-free desktop control system.

The assistant uses **MediaPipe** to detect hand gestures, **OpenCV** for face and eye tracking, and **pyttsx3** for text-to-speech responses — turning your webcam into a smart human-computer interface.

---

## ⚙️ Features

✅ **👁️ Eye Detection & Fatigue Alert**

* Detects if your eyes are closed for more than 5 seconds.
* Triggers an audio alert: *“Alert! Please open your eyes.”*

✅ **✋ Hand Gesture Recognition**

* Detects your right-hand gestures using MediaPipe.
* Opens applications or websites based on your finger combinations.

✅ **🗣️ Voice Feedback System**

* Uses `pyttsx3` to speak system responses.
* Greets you on start-up and confirms every action verbally.

✅ **🌐 Smart System Integration**

* Opens web apps (YouTube, Hotstar, etc.) and system apps (Notepad, Camera, Edge) directly from hand gestures.
* Automatically terminates any previously opened process before launching a new one.

---

## 🧩 Gesture Control Mappings

| Gesture (Right Hand)               | Action              |
| ---------------------------------- | ------------------- |
| ☝️ (Index finger up)               | Open YouTube        |
| ✌️ (Index + Middle)                | Open Hotstar        |
| 🤟 (Index + Middle + Ring)         | Open Camera         |
| 🖖 (Index + Middle + Ring + Pinky) | Open Microsoft Edge |
| 🖐️ (All fingers up)               | Open Notepad        |

---

## 🧠 Tech Stack

* **Python 3.8+**
* **OpenCV** – for face & eye detection
* **MediaPipe** – for hand gesture recognition
* **pyttsx3** – for speech synthesis
* **subprocess / webbrowser / os** – for system automation

---

## 🖥️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/AI-Virtual-Assistant.git
cd AI-Virtual-Assistant
```

### 2️⃣ Install dependencies

```bash
pip install opencv-python mediapipe pyttsx3
```

### 3️⃣ Run the program

```bash
python virtual_assistant.py
```

---

## ⚡ How It Works

1. The webcam feed is processed frame-by-frame using **OpenCV**.
2. **MediaPipe Hands** detects hand landmarks and identifies finger positions.
3. Specific finger patterns are mapped to apps/websites.
4. **OpenCV Haar Cascades** detect eyes — if closed for too long, a **fatigue alert** is triggered.
5. The **TTS engine** speaks every system action for better user interaction.

---

## 🧠 Future Enhancements

🚀 AI voice command support using **SpeechRecognition**
🧍‍♂️ Body pose detection for full-body gesture control
💬 Integration with **ChatGPT API / LangChain** for intelligent Q&A
🎧 Add wake-word detection (“Hey Assistant”)
🌗 GUI dashboard to manage gesture mappings

---

## 🧑‍💻 Developer

**👨‍💻 Developer:** **
**🔗 Skills:** Computer Vision, Python Automation, Machine Learning, Cybersecurity
**💼 Organization:** Goklyn Private Limited, Jaipur

---

## 🛡️ Disclaimer

This project is built purely for educational and research purposes. It should not be used for any form of surveillance or privacy-invasive tasks without consent.

---

## ⭐ Contribution

Contributions are welcome!
Fork the repo, create a feature branch, and submit a pull request.

```bash
git checkout -b feature/your-feature
git commit -m "Added a new gesture command"
git push origin feature/your-feature
```

---
