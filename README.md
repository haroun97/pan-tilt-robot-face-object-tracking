# 🤖 Pan-Tilt Head Robot with Camera  
### Object & Face Detection and Tracking using OpenCV

> 🎯 Phase 1 of an Autonomous Robot Arm for assisting people with reduced mobility

---

## 📌 Overview

This project presents a **Pan-Tilt Head Robot** capable of detecting and tracking objects and human faces using computer vision.

The system combines **hardware (servo motors + Arduino)** and **software (Python + OpenCV)** to automatically adjust the camera position and keep the target centered.

---

## 🎥 Demo

See the Pan-Tilt Robot detecting and tracking objects in real-time:

[![Watch the demo](https://img.youtube.com/vi/yPaVLf3wQvo/0.jpg)](https://www.youtube.com/watch?v=yPaVLf3wQvo)

## 🚀 Objective

- Detect faces and objects in real-time
- Track the target dynamically
- Control camera movement using servo motors
- Build the foundation for an assistive robotic system

---

## 🧠 Project Context

This project represents **Phase 1** of a larger system:

### 👉 Autonomous Robot Arm (Main Project)

An intelligent robotic arm designed to assist people with reduced mobility to:
- 🍽️ Eat
- 🥤 Drink
- 💊 Take medication

📅 Aug 2020 – Jul 2021

The Pan-Tilt system was developed as the **vision and tracking module** for this robotic arm.

---

## 🏗️ System Architecture

### 🔄 Workflow

1. 📷 Camera captures real-time video
2. 🧠 Computer processes frames using OpenCV
3. 🎯 Object/Face is detected
4. 📡 Coordinates are calculated
5. 🔁 Commands are sent to Arduino
6. ⚙️ Servo motors adjust camera position (pan & tilt)

---

## ⚙️ Components

### 🔵 Hardware
- Arduino Uno
- 2x Servo Motors (Pan & Tilt)
- Camera Module
- Pan-Tilt Mechanism

### 🔵 Software
- Python
- OpenCV
- Arduino IDE

---

## 🛠️ Technologies Used

- Computer Vision (OpenCV)
- Embedded Systems
- Serial Communication (Python ↔ Arduino)
- Real-time Image Processing

---
## 📚 References & Learning Resources

This project was built with the help of the following tutorials and articles:

- 🎯 Adrian Rosebrock — *Ball Tracking with OpenCV*  
  https://www.pyimagesearch.com/2015/09/14/ball-tracking-with-opencv/

- 👤 Towards Data Science — *Real-Time Object Detection with OpenCV*  
  https://towardsdatascience.com/real-time-object-detection-with-opencv-python-8b2c4c1c0b64
  

## 📂 Project Structure

```bash
.
├── Objects_and_Faces_Tracking/   # Main tracking scripts
├── README.md
