# Drowsiness-Detection

## Overview
Drowsiness while driving is a major cause of road accidents, leading to injuries and fatalities. This project aims to develop a real-time drowsiness detection system using YOLOv3 (You Only Look Once v3), an advanced deep learning-based object detection model. The system continuously monitors a driver's eyes and mouth movements to detect signs of drowsiness and issues an alert if necessary.

## Features
Real-time detection of drowsiness using a webcam.
YOLOv3-based object detection for recognizing closed eyes and yawning.
Alert system that triggers an alarm when drowsiness is detected.
High accuracy and efficiency using deep learning techniques.
Optimized for real-time performance with OpenCV and TensorFlow.

## Technologies Used
Python
OpenCV (for image and video processing)
TensorFlow 2.13.0 (for deep learning model training and inference)
YOLOv3 (for object detection)
Matplotlib (for data visualization)
NumPy (for numerical computations)

## Installation
pip install -r requirements.txt

## Model-Performance
Accuracy: 98%
Training Loss: 0.04 (4%)
Validation Loss: 0.05 (5%)

## To clone the GitHub repository:
git clone https://github.com/Venkata-Jayanth04/Drowsiness-Detection.git

## Project Outputs:

### Non-Drowsy:
<img src="https://github.com/user-attachments/assets/31db103b-26f4-47be-8bff-c8f935be3397" alt="Non-Drowsy" width="500">

### Drowsy:
<img src="https://github.com/user-attachments/assets/7ba1efdd-c008-49b6-8127-cca4a59061b9" alt="Drowsy" width="500">

How It Works
The system captures a video feed from a webcam.
It detects the eyes and mouth using the YOLOv3 model.
If the eyes remain closed for a certain duration, the system identifies drowsiness.
If yawning is detected, the system increases the drowsiness score.
If the drowsiness score crosses a threshold, an alarm is triggered.
