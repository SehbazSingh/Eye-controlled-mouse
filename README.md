# 🖱️ Eye Controlled Mouse

Control your mouse using just your eyes! This Python project leverages **MediaPipe**, **OpenCV**, and **PyAutoGUI** to detect facial landmarks in real time and map eye movements to cursor actions. When you blink, it simulates a mouse click.

---


## 🧠 How It Works

- Uses **MediaPipe Face Mesh** to track facial landmarks.
- Maps the position of your **right eye** to your screen coordinates.
- Detects **blinks** with the **left eye** to trigger mouse clicks.
- Works in **real-time** using your webcam.

---

## 🛠️ Requirements

Install dependencies with:

```bash
pip install opencv-python mediapipe pyautogui
