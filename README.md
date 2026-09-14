# 🧠 Handwritten Character Recognition using CNN

A deep learning project that recognizes handwritten digits using a Convolutional Neural Network (CNN) trained on the MNIST dataset.

## 📌 Project Overview

This project uses a CNN to classify handwritten digits from 0 to 9.

The model learns visual patterns from thousands of handwritten digit images and predicts the digit present in a new image.

## 🚀 Features

- Handwritten digit classification (0–9)
- CNN-based deep learning model
- MNIST dataset
- Image normalization and preprocessing
- Model training and evaluation
- Digit prediction on unseen images

## 🧠 CNN Architecture

The model consists of:

- Convolutional Layers
- Max Pooling Layers
- Flatten Layer
- Fully Connected (Dense) Layers
- Dropout for reducing overfitting
- Softmax output layer for digit classification

### Workflow

```text
MNIST Dataset
      ↓
Data Preprocessing
      ↓
Convolutional Layers
      ↓
Pooling Layers
      ↓
Flatten
      ↓
Dense Layers
      ↓
Softmax
      ↓
Predicted Digit (0–9)
