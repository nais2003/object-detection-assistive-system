# 🦯 Object Detection Assistive System for Visually Impaired People

This project aims to assist blind and visually impaired individuals in navigating their environment safely using real-time object detection and audio feedback.

## 📌 Overview

Developed as part of a university project by a team of five students, this system uses a camera to detect obstacles (such as people, vehicles, and stairs) and provides spoken alerts using text-to-speech technology. Our goal is to enhance independence and mobility for the visually impaired.

## 👥 Team Members
- Naima SAIDI  
- Hind Ait TEMGHART  
- Salah Edine HAJJIOUI 
- Ahmed Nour ELBOURKADI  
  

## ⚙️ Technologies Used
- Python
- [YOLOv8](https://github.com/ultralytics/ultralytics) (for object detection)
- OpenCV (for image/video processing)
- pyttsx3 or gTTS (for text-to-speech)
- Real-time webcam input

## 🧠 How It Works
1. Captures live video from a webcam
2. Runs YOLOv8 to detect objects in the frame
3. Converts detected object labels into audio messages
4. Plays audio to inform the user of nearby obstacles
