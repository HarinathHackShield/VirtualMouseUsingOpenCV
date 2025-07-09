# 🖱️ AI Virtual Mouse (Gesture-Controlled Interface)

Control your computer using hand gestures captured through a webcam! This project utilizes Python, OpenCV, and MediaPipe to simulate mouse movements, clicks, and drag events—without touching a physical device.

## 🧠 Features

- Real-time hand tracking with fingertip detection  
- Move the mouse pointer by moving your hand  
- Pinch gesture for click functionality  
- Smooth cursor control with frame interpolation  
- Drag and drop support (optional)

---

## 🚀 Technologies Used

- 🐍 Python
- 🎯 MediaPipe (Google)
- 🎥 OpenCV
- 🖐️ Hand Tracking Module
- 💻 Real-Time Computer Vision

---

## 🔧 Installation

```bash
# Clone this repository
git clone https://github.com/HarinathHackShield/VirtualMouseUsingOpenCV.git
cd VirtualMouseUsingOpenCV

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install required packages
pip install opencv-python mediapipe pyautogui numpy
