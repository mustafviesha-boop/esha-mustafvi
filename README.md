# 💤 Drowsiness and Eye Gaze Alert System

## 📌 Project Overview
This project is a real-time driver monitoring system designed to detect drowsiness and improper eye gaze using computer vision techniques. The system alerts the driver when signs of fatigue or distraction are detected, helping to reduce road accidents.

---

## 🎯 Objectives
- Detect driver drowsiness using eye closure analysis
- Monitor eye gaze direction
- Provide real-time alerts
- Enhance road safety using AI

---

## 🛠️ Technologies Used
- Python
- OpenCV
- Dlib / MediaPipe
- NumPy
- PyGame / Playsound (for alerts)

---

## ⚙️ How It Works
1. Captures live video from webcam
2. Detects face and eye landmarks
3. Calculates Eye Aspect Ratio (EAR)
4. Tracks eye gaze movement
5. Triggers alert if drowsiness is detected

---

## ▶️ How to Run the Project
```bash
pip install opencv-python numpy dlib mediapipe
python main.py

