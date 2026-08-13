# Hand-Written-Digit-Recognition

A deep learning project for recognizing handwritten digits (0–9) using a Convolutional Neural Network (CNN) with TensorFlow/Keras.

📌 Overview

This project uses the MNIST dataset to train a CNN model that classifies handwritten digit images.

Dataset
60,000 training images
10,000 test images
Image size: 28 × 28 pixels
10 classes (0–9)
🧠 Model Architecture
Input (28×28×1)
      ↓
Conv2D (32 filters)
      ↓
MaxPooling
      ↓
Conv2D (64 filters)
      ↓
MaxPooling
      ↓
Flatten
      ↓
Dense (128)
      ↓
Dropout (30%)
      ↓
Output (10 classes)
📊 Features
MNIST dataset preprocessing
CNN model training
Training/validation accuracy and loss visualization
Test-set evaluation
Single and multiple digit prediction
Model saving and loading
🛠️ Technologies
Python
TensorFlow / Keras
NumPy
Matplotlib
📈 Result

The trained CNN achieves high accuracy on the MNIST test dataset and can correctly recognize handwritten digits.

🎯 Learning Outcomes
Understanding CNNs
Image preprocessing
Model training and evaluation
Digit classification
Saving and loading deep learning models
