# MNIST Digit Classification using ANN

This project implements a simple Artificial Neural Network (ANN) to classify handwritten digits (0–9) from the MNIST dataset using Python and TensorFlow/Keras.

---

##  Overview

The MNIST dataset is a collection of 70,000 handwritten digit images (28x28 pixels) split into training and testing sets. The goal is to train a neural network to correctly identify digits based on pixel data.

---

##  Model Architecture

- **Input Layer**: 784 neurons (28x28 pixels flattened)
- **Hidden Layer(s)**: 1–2 Dense layers with ReLU activation
- **Output Layer**: 10 neurons with Softmax (for digits 0–9)
---

## Layer
 - model = Sequential([
    Dense(128, activation='relu', input_shape=(784, ), activation= 'relu'),
    Dense(10, activation='softmax')
])

---

## 🚀 Technologies Used

- Python

- TensorFlow / Keras

- NumPy

- Matplotlib (for visualization)

- MNIST dataset (via tensorflow.keras.datasets)
