# AR-Based Navigation Assistance System for the Visually Impaired

## Overview

This project is an assistive navigation solution designed to support visually impaired users by combining real-time object detection, augmented reality (AR) technology, and audio guidance. The system interprets the user’s environment using computer vision and provides relevant audio feedback to help navigate safely.

This repository includes the project documentation and the official paper publication certificate.

---

## Features

- **Real-time Obstacle Detection**  
  Uses a deep learning model to detect obstacles and common objects from a live camera feed.

- **Augmented Reality (AR) Integration**  
  Provides spatial awareness and environment interpretation using AR capabilities in Unity.

- **Audio Guidance**  
  Generates voice alerts and descriptive feedback to guide the user using text-to-speech.

---

## How It Works

1. The device camera captures live video feed.
2. A trained object detection model processes each frame to identify obstacles.
3. Detected information is passed to the AR framework for scene interpretation.
4. Relevant audio guidance is generated and delivered to the user in real time.

---

## Technologies Used

- **YOLOv5** – Real-time object detection model used for detecting surrounding objects and obstacles.
- **Unity Engine** – Project developed within Unity for AR integration and application logic.
- **Unity AR Framework** – Used for rendering AR visuals and environmental context.
- **Unity Sentis** – Used for on-device neural network inference of the detection model.
- **Google Text-to-Speech (TTS)** – Converts guidance text into spoken audio feedback.
- **Computer Vision & AI / ML** – Core logic for processing and interpreting environmental data.

---

## Certificate

The official paper publication certificate can be viewed here:  
**[Paper Publication Certificate (Blind Navigation using AR)](https://github.com/mmkyadav/Blind-Navigation_using_AR/blob/30784203b13176f77e882333d44947aa1b3bbe2b/Paper%20publication%20certificate.jpeg)**

---

## Repository Contents

- `README.md` – Project explanation and details  
- `Project_Report.pdf` – Detailed documentation describing the problem, design, and methodology (if included)  
- `Paper publication certificate.jpeg` – Certificate confirming presentation of the work  

---

## Limitations

- Prototype-level implementation intended for feasibility validation.
- Performance varies with lighting conditions and camera quality.
- Requires further optimization for real-time use on low-power AR devices.

---

## Future Work

- Re-implement a minimal demo version for real-time testing.
- Extend object classes to include more environmental features.
- Integrate with wearable AR headsets for hands-free use.
- Conduct user testing with visually impaired individuals for feedback-driven improvements.

---

## Author

M. Muddu Krishna
