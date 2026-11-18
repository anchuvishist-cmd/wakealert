
# 🚗 Wakealert – AI-Based Driver Drowsiness Detection System

## 📌 About the Project

**Wakealert** is an AI-powered Driver Drowsiness Detection System designed to improve road safety by monitoring a driver's facial expressions and detecting signs of sleepiness and fatigue in real time.

The system uses computer vision and facial landmark detection to monitor eye movements, yawning, and head position. Whenever signs of drowsiness are detected, the system triggers an audio alarm to alert the driver and help prevent accidents.

The main objective of WakeUpXAI is to make driving safer by providing an intelligent, real-time driver monitoring solution.

## 🎯 Objectives

- Detect driver drowsiness in real time.
- Monitor eye movements and blinking patterns.
- Detect yawning to identify fatigue.
- Identify abnormal head positioning.
- Generate an audio alert when drowsiness is detected.
- Display the driver's current status and safety score.

## ✨ Key Features

- **Real-Time Face Detection:** Detects facial landmarks using MediaPipe.
- **Eye Monitoring:** Monitors eye closure to identify possible sleepiness.
- **Yawning Detection:** Detects mouth movements associated with yawning.
- **Head Position Detection:** Identifies when the driver's head moves downward.
- **Audio Alert System:** Plays an alarm when drowsiness is detected.
- **Driver Safety Score:** Displays a score starting from 100.
- **Live Webcam Monitoring:** Processes video directly through the webcam.
- **Interactive GUI:** Provides a desktop interface using Tkinter.
- **Screenshot Capture:** Saves an image when drowsiness is detected.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| OpenCV | Image processing and webcam access |
| MediaPipe | Facial landmark detection |
| Tkinter | Graphical user interface |
| Pillow | Image conversion and display |
| Pygame | Audio alarm system |
| Math | Distance calculations |

## 📂 Project Structure

Wakealert/
│
├── main.py
├── alarm.mp3
├── README.md
├── requirements.txt
└── venv/

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/BlueeWhale/WakeX-AI.git
```

### 2. Open the Project Folder

```bash
cd Wakealert
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### 5. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 6. Run the Application

```bash
python main.py
```

## 📦 Requirements

Create a `requirements.txt` file with:

```text
opencv-python
mediapipe==0.10.21
Pillow
pygame
```

**Note:** Python 3.12 is recommended for this project.

## 🖥️ How It Works

1. The system accesses the webcam.
2. OpenCV captures live video frames.
3. MediaPipe identifies facial landmarks.
4. Eye distance is calculated to detect possible eye closure.
5. Mouth distance is measured to identify yawning.
6. Nose position is monitored to detect downward head movement.
7. If drowsiness is detected, an audio alarm is activated.
8. The GUI displays the driver's status and safety score.

## 🚀 Future Enhancements

- Improve eye closure detection using blink duration.
- Implement more accurate head pose estimation.
- Add mobile application support.
- Integrate advanced machine learning models.
- Store driver monitoring history and reports.
- Add cloud-based monitoring and analytics.
- Improve performance in low-light conditions.

## 👩‍💻 Project Information

**Project Name:** Wakealert

**Project Type:** AI-Based Driver Monitoring System

**Domain:** Artificial Intelligence and Computer Vision

**Programming Language:** Python

**Application Type:** Desktop Application

## ❤️ Acknowledgement

WakeUpXAI is developed with the aim of using Artificial Intelligence and Computer Vision to promote safer driving and reduce accidents caused by driver fatigue.

**Stay Alert. Stay Awake. Stay Safe! 🚗**
