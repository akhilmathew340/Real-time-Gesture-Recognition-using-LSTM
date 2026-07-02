# Real-time-Gesture-Recognition-using-LSTM
Real-time gesture recognition using LSTM, MediaPipe Holistic, OpenCV, and TensorFlow for dynamic human gesture classification.


## Overview

This project implements a real-time Gesture Recognition system using Long Short-Term Memory (LSTM) networks and MediaPipe Holistic. The system captures body, hand, and facial landmarks from live webcam input and classifies dynamic gestures using a trained deep learning model.

The project demonstrates the application of computer vision and deep learning techniques for human gesture recognition, enabling touchless interaction and intelligent human-computer interfaces.

---

## Features

- Real-time gesture recognition using webcam
- Human pose, face, and hand landmark detection
- LSTM-based sequence classification
- Dynamic gesture prediction
- Live prediction visualisation
- Deep learning model training and evaluation

---

## Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- MediaPipe
- NumPy
- Matplotlib
- Scikit-learn

---

## Project Workflow

1. Capture live webcam input
2. Detect body, face, and hand landmarks using MediaPipe Holistic
3. Extract sequential keypoints
4. Train the LSTM model
5. Perform gesture prediction
6. Display real-time recognised gestures

---

## Deep Learning Model

Model Architecture:

- LSTM Layer (64 units)
- LSTM Layer (128 units)
- LSTM Layer (64 units)
- Dense Layer (64 units)
- Dense Layer (32 units)
- Softmax Output Layer

Optimizer:
- Adam

Loss Function:
- Categorical Crossentropy

---

## Applications

- Human-Computer Interaction
- Gesture-Based Control Systems
- Smart Automation
- Assistive Technology
- Touchless Interfaces
- Healthcare Applications

---

## Future Improvements

- Support additional gesture classes
- Improve prediction accuracy using larger datasets
- Integrate with IoT devices
- Deploy as a web application
- Mobile application integration

---

## Author

**Akhil Mathew Cherian**

MSc Data Science | Data Analytics | Machine Learning | Deep Learning
