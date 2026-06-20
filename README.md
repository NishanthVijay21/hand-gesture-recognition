# ✋ Real-Time Hand Gesture Recognition

This project implements a Convolutional Neural Network (CNN) to recognize hand gestures in real-time using a live webcam feed. It utilizes **Keras/TensorFlow** for building and training the deep learning model, and **OpenCV** for live video capture and background subtraction.

## ✨ Features
* **Custom CNN Architecture:** A lightweight deep learning model featuring Convolutional, MaxPooling, Batch Normalization, and Dropout layers for robust feature extraction.
* **Background Subtraction:** Uses running average algorithms to dynamically separate the foreground (hand) from the background in the live video feed.
* **Real-Time Inference:** Captures frames via webcam, segments the hand, and displays the predicted gesture directly on the screen.
* **6 Supported Gestures:** Recognizes `Blank`, `OK`, `Thumbs Up`, `Thumbs Down`, `Fist`, and `Five`.

## 🛠️ Tech Stack
* **Python 3.x**
* **Deep Learning:** Keras, TensorFlow
* **Computer Vision:** OpenCV (`cv2`)
* **Data Processing:** NumPy, Scikit-Learn
