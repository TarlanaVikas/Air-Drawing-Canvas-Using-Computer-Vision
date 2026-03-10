
# 🖌️ Air Drawing Canvas Using Computer Vision

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv)
![NumPy](https://img.shields.io/badge/NumPy-Matrix%20Ops-orange?logo=numpy)

An interactive, touchless drawing application built with Python and OpenCV that lets users draw on a virtual canvas using a colored object as a pen—no physical contact required.

## 🚀 Overview

This project transforms your webcam into a gesture-based drawing tool. By detecting and tracking a colored marker in real time, users can sketch freely in the air. The app features dynamic color selection, canvas clearing, and smooth stroke rendering—all controlled by simple hand movements.

- Developed by **Tarlana Vikas** 
- Hackathon: **HackZilla**  
- Statement Code: **CV-06**

## 🎯 Objective

To create a real-time virtual drawing experience using computer vision, enabling users to:
- Draw using a colored object (e.g., marker or cap)
- Switch between brush colors (Blue, Green, Red, Yellow)
- Clear the canvas with a gesture
- Interact without touching the screen

## 🧰 Tech Stack

- **Python 3.x**
- **OpenCV** – for image processing and object tracking
- **NumPy** – for matrix operations and morphological transformations
- **Webcam** – for live video input

## 🧪 Methodology

1. **Capture webcam feed**
2. **Convert frames to HSV color space**
3. **Use trackbars to tune HSV values**
4. **Apply morphological operations to clean the mask**
5. **Detect contours and locate the marker**
6. **Draw lines based on marker movement**
7. **Switch colors or clear canvas via virtual buttons**

## 🎨 Features

- Real-time object tracking using HSV filtering
- Gesture-based color switching and canvas clearing
- Smooth freehand drawing with deque-based stroke management
- Modular code with clear separation of logic and UI

---

## 🛠️ Setup & Installation

Follow these steps to get the Air Drawing Canvas running on your local machine:

### 1. 📦 Prerequisites

Make sure you have the following installed:

- Python 3.6 or higher
- A working webcam
- pip (Python package manager)

### 2. 📁 Clone the Repository

```bash
git clone https://github.com/TarlanaVikas19/Air-Drawing-Canvas-Using-Computer-Vision.git
cd Air-Drawing-Canvas-Using-Computer-Vision
```

### 3. 📚 Install Required Libraries

Use the following command to install dependencies:

```bash
pip install opencv-python numpy
```

### 4. ▶️ Run the Application

Launch the app using:

```bash
python air_drawing.py
```

> Replace `air_drawing.py` with the actual filename if different.

### 5. 🎯 Usage Tips

- Use a brightly colored object (e.g., red or blue cap) for best tracking.
- Adjust HSV values using the on-screen trackbars to fine-tune detection.
- Hover over virtual buttons to switch colors or clear the canvas.

---


## 📸 Screenshots

- Initial interface with HSV trackbars
- Marker detection in action
- Color switching via gestures
- Canvas clearing
- Final painted output

## 🧠 Challenges

- HSV tuning under variable lighting
- Managing drawing continuity with deques
- Accurate gesture detection for button interaction
- Minimizing frame lag for smooth UX

## 🔮 Future Enhancements

- Gesture-based color selection (no buttons)
- Shape drawing (circles, rectangles)
- Save canvas as image
- Multi-marker support for collaborative drawing
- Voice command integration

## 📚 References

- [OpenCV Documentation](https://docs.opencv.org/)
- Stack Overflow threads on HSV tuning and contour detection
- GitHub examples of gesture-based drawing apps

---
