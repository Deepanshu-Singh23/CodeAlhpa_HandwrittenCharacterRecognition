# 🧠 Handwritten Character Recognition using CNN

A deep learning project that recognizes handwritten digits using a Convolutional Neural Network (CNN) trained on the MNIST dataset.

## 📌 Project Overview

This project uses a Convolutional Neural Network (CNN) to classify handwritten digits from **0 to 9**.

The model learns visual patterns from handwritten digit images and predicts the digit present in a new image.

## 🚀 Features

- Handwritten digit classification (0–9)
- CNN-based deep learning model
- MNIST dataset
- Image normalization and preprocessing
- Model training and evaluation
- Accuracy and loss visualization
- Confusion matrix analysis
- Digit prediction on unseen data

## 🧠 CNN Architecture

The model consists of:

- Convolutional Layers
- Max Pooling Layers
- Flatten Layer
- Fully Connected (Dense) Layers
- Dropout for reducing overfitting
- Softmax output layer for digit classification

## 🔄 How It Works

1. **Load MNIST Dataset** – Load handwritten digit images for training and testing.
2. **Preprocess Images** – Normalize pixel values and reshape images for CNN input.
3. **Train CNN Model** – Extract important visual features using convolution and pooling layers.
4. **Classify Digits** – Use fully connected layers and Softmax to classify digits from 0–9.
5. **Evaluate Model** – Measure performance using accuracy, loss, and a confusion matrix.

## 📊 Dataset

The project uses the **MNIST handwritten digit dataset**.

- **Training Images:** 60,000
- **Testing Images:** 10,000
- **Image Size:** 28 × 28 pixels
- **Number of Classes:** 10 (digits 0–9)

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Jupyter Notebook
- Google Colab
- Convolutional Neural Networks (CNN)

## 📈 Model Performance

The CNN model was trained for **5 epochs**.

| Metric | Result |
|---|---:|
| Training Accuracy | 95.68% |
| Validation Accuracy | 96.80% |
| Training Loss | 0.1423 |
| Validation Loss | 0.1117 |
| Total Parameters | 121,930 |


## 📂 Project Structure

```text
CodeAlpha_HandwrittenCharacterRecognition/
│
├── CodeAlpha_HandwrittenCharacterRecognition.ipynb
├── README.md
├── requirements.txt
├── .gitignore
│
└── results/
    ├── Training vs Validation Accuracy.png
    ├── Training vs Validation Loss.png
    └── MNIST CNN Confusion Matrix.png
