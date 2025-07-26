# 🎮 Subway Surfers Hand Gesture Controller

Control the popular **Subway Surfers** game using just your **hand gestures**!  
This project uses **Python**, **OpenCV**, and **MediaPipe** to detect real-time hand movements via webcam and map them to keyboard inputs — allowing you to play the game touch-free. 🖐️➡️💻

---

## 🧠 Project Objective

To build a computer vision-based system that detects **hand gestures in real-time** and uses them to control the **Subway Surfers** game using simulated keystrokes (left, right, jump, roll).

---

## 🎥 How It Works

- 👁️ Webcam captures live video
- 🧠 MediaPipe detects hand landmarks (e.g., palm, fingers)
- 🎯 Specific gestures (like swipes or finger positions) are mapped to:
  - **Left/Right Swipe** → Move left/right
  - **Hand Up** → Jump
  - **Hand Down** → Roll
- 💻 PyAutoGUI or `keyboard` library simulates the required keyboard key press

---

## 🛠️ Technologies Used

| Tool/Library     | Purpose                                 |
|------------------|------------------------------------------|
| Python           | Main programming language                |
| OpenCV           | Access webcam and process image frames   |
| MediaPipe        | Real-time hand tracking and gesture detection |
| PyAutoGUI/keyboard | Simulate keyboard inputs to game        |
| Numpy            | Image processing and matrix operations   |

---

## 📁 Folder Structure

subway-hand-gesture/
│
├── hand_gesture_controller.py # Main script
├── requirements.txt # Python dependencies
├── utils/ # Utility scripts (optional)
├── assets/ # Gesture reference images (optional)
└── README.md # Project documentation
