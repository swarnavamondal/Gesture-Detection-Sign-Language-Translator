# Gesture-Detection-Sign-Language-Translator
Real-time gesture detection and sign language translation model using LSTM neural networks, TensorFlow, MediaPipe, and OpenCV. Achieves ~98% accuracy.

# Real-Time Sign Language Translation using LSTM

This project is a real-time gesture detection and sign language translation system built using deep learning and computer vision. Leveraging **TensorFlow**, **MediaPipe**, **OpenCV**, and **LSTM neural networks**, this model is capable of recognizing sign language gestures with ~98% accuracy.

---

## 🚀 Features

- Real-time gesture recognition via webcam
- Hand landmark detection using **MediaPipe**
- LSTM model for sequential gesture classification
- High accuracy (~98%)
- Clean and interactive Jupyter Notebook
- Modular and easy to extend for new gestures

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- TensorFlow / Keras
- OpenCV
- MediaPipe
- NumPy, Pandas, Matplotlib

---

## 📊 Model Architecture

- **Input**: Sequences of 3D hand landmarks
- **Model**: LSTM-based neural network
- **Output**: Predicted gesture/sign class

```plaintext
Input (Landmarks) → LSTM Layers → Dense Layers → Softmax Output
