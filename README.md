# IntelliRehab-Physiotherapy

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![PyQt5](https://img.shields.io/badge/PyQt5-GUI-brightgreen.svg)](https://pypi.org/project/PyQt5/)
[![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-yellow.svg)](https://opencv.org/)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-Pose%20Tracking-orange.svg)](https://google.github.io/mediapipe/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-AI-red.svg)](https://www.tensorflow.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-AI-red.svg)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**IntelliRehab-Physiotherapy** is a Python-based, AI-powered rehabilitation application that assists users in recovering from joint injuries and physiotherapy exercises safely. It leverages **motion tracking via webcam**, provides **real-time feedback**, and monitors progress to ensure exercises are performed correctly.

[![DEMO1](project_img1.jpg)](project_img1.jpg)
[![DEMO2](project_img2.jpg)](project_img2.jpg)

---

## Table of Contents

1. [Project Structure](#project-structure)
2. [Inspiration](#inspiration)
3. [What It Does](#what-it-does)
4. [How We Built It](#how-we-built-it)
5. [Key Features](#key-features)
6. [Getting Started](#getting-started)

   * [Prerequisites](#prerequisites)
   * [Installation](#installation)
   * [Running the Application](#running-the-application)
7. [Future Enhancements](#future-enhancements)
8. [License](#license)
9. [Author](#author)

---

## Project Structure

```plaintext
IntelliRehab-Physiotherapy/
│
├── assets/               # Media assets (images, videos, etc.)
├── gui/                  # GUI-related code and layout
├── modules/              # Exercise modules (knee, back, shoulder exercises)
├── tutorials/            # Documentation and instructional material
├── utils/                # Utility functions
├── .gitignore            # Git ignore rules
├── README.md             # Project documentation
├── __init__.py           # Package marker
├── app.log               # Log file for application errors or events
├── main.py               # Main entry point for the application
├── progress.db           # Local database for tracking progress
├── requirements.txt      # Dependencies list
├── test_webcam.py        # Script for testing webcam and motion tracking
└── view_progress.py      # View progress and stats over time
```

---

## Inspiration

IntelliRehab-Physiotherapy addresses challenges faced by patients undergoing **post-surgery or joint injury rehabilitation**. Maintaining correct posture usually requires frequent supervision, which is **costly and time-consuming**.

This project provides a **smart, accessible solution** for monitoring exercises, tracking progress, and receiving **real-time corrective feedback**.

---

## What It Does

* Tracks users’ movements and analyzes exercise form in **real-time** using computer vision.
* Provides **corrective feedback** to reduce re-injury risks.
* Offers **personalized exercise recommendations** based on performance.
* Incorporates **gamification elements** to motivate users.
* Supports multiple types of rehabilitation exercises, including **knee, shoulder, and joint mobility exercises**.

---

## How We Built It

* **MediaPipe** – pose tracking and motion analysis
* **OpenCV** – real-time video processing
* **NumPy** – data manipulation
* **PyQt5** – interactive GUI
* **TensorFlow / PyTorch** – AI model integration for exercise recognition and feedback

This allows **accurate posture analysis**, exercise recommendations, and progress tracking.

---

## Key Features

1. **Real-time motion tracking** – ensures correct posture.
2. **Progress monitoring** – tracks improvement over time.
3. **Exercise suggestions & modifications** – adapts difficulty dynamically.
4. **Gamification & motivation** – encourages consistent exercise.
5. **User-friendly GUI** – accessible for all ages and technical skills.

---

## Getting Started

### Prerequisites

* Python 3.8 or higher
* OpenCV
* TensorFlow or PyTorch
* Other dependencies in `requirements.txt`

---

### Installation

```bash
# Clone the repository
git clone https://github.com/shubhamay09/IntelliRehab-Physiotherapy.git

# Navigate to project directory
cd IntelliRehab-Physiotherapy

# Create virtual environment (optional)
python -m venv venv

# Activate virtual environment
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

---

### Running the Application

```bash
python main.py
```

Launches the **IntelliRehab-Physiotherapy GUI** for real-time rehabilitation exercise tracking.

---

## Future Enhancements

* Voice guidance for exercises
* Integration with wearable sensors
* Personalized exercise plans based on medical history
* Exportable progress reports for physiotherapists

---

## License

This project is licensed under the **MIT License** – see LICENSE for details.

---

## Author

**Shubhamay Santra**
AI and computer vision enthusiast dedicated to improving healthcare through technology.

---
