# MNIST Classification using ANN

A simple Artificial Neural Network (ANN) model to classify handwritten digits from the MNIST dataset.

## 📋 About the Project

This project implements a basic neural network to recognize handwritten digits (0-9) using the MNIST dataset. The model achieves **96.94% accuracy** on test data.

## 🏗️ Model Architecture

- **Input**: 28x28 pixel images (flattened to 784 features)
- **Hidden Layer 1**: 128 neurons with ReLU activation (L2 regularization)
- **Hidden Layer 2**: 32 neurons with ReLU activation (L2 regularization)
- **Output Layer**: 10 neurons with Softmax activation

## 📊 Results

- Test Accuracy: **96.94%**
- Training accuracy and loss curves are included in the notebook

## 🛠️ Technologies Used

- TensorFlow / Keras
- Python
- Matplotlib
- Scikit-learn

## 🚀 How to Run

1. Open the `mnist11.ipynb` notebook
2. Run all cells to train the model and see results

## 📁 Files

- `mnist11.ipynb` - Main notebook with model implementation
- Training and validation plots included
