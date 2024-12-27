# Driver Fatigue Monitoring System

## Overview
Driver fatigue is a major cause of road accidents worldwide, posing a significant threat to road safety. 
The **Driver Fatigue Monitoring System** is a real-time solution designed to detect signs of driver 
drowsiness and prevent accidents. Using Convolutional Neural Networks (CNNs), this system monitors 
drivers for fatigue indicators such as eye closure, blinking patterns, and mouth movements.

## Features
- **Real-Time Monitoring**: Uses a webcam to capture video streams of the driver's face.
- **Fatigue Detection**: Analyzes facial features (eye openness, blinking rate, and mouth movement) with a CNN model to detect drowsiness.
- **Alert System**: Sends a warning alarm when fatigue is detected, to warn the driver to take a break.
- **Cost-Effective**: A simple and affordable solution for improving road safety.
- **Ease of Use**: Works seamlessly in real-time without requiring specialized hardware.

## Technologies Used
- **Machine Learning (Deep Learning)**: Convolutional Neural Networks (CNNs)
- **Programming Language**: Python
- **Libraries and Frameworks**:
  - OpenCV (for video processing)
  - TensorFlow/Keras (for CNN model)
  - NumPy, Pandas (for data handling)

## How It Works
1. **Video Capture**: The system uses a webcam to record live video of the driver.
2. **Feature Extraction**: Key facial features (eyes and mouth) are detected and analyzed using OpenCV.
3. **Prediction**: A trained CNN model determines if the driver is alert or drowsy based on these features.
4. **Alert Mechanism**: If drowsiness is detected, an alert message/alarm is generated to warn the driver.
   
