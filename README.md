# Handwritten-Digit-Recognition-ANN

A simple machine learning project that recognizes handwritten digits (0–9) using an **Artificial Neural Network (ANN)** built with TensorFlow and Keras.

## Overview
This project uses the **MNIST dataset** to train a neural network model capable of classifying handwritten digits.  
The model consists of fully connected layers (Dense layers) and uses **ReLU** and **Softmax** activations to achieve high accuracy on the test dataset.

## Features
- Handwritten digit classification (0–9)
- Uses TensorFlow and Keras Sequential API
- Trains and validates on the MNIST dataset
- Accuracy visualization using Matplotlib

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn
- Google Colab

## Model Architecture
- Input Layer: Flatten (28×28 images)
- Hidden Layer 1: Dense (128 neurons, ReLU)
- Hidden Layer 2: Dense (32 neurons, ReLU)
- Output Layer: Dense (10 neurons, Softmax)

## Training Details
- Optimizer: Adam  
- Loss Function: Sparse Categorical Crossentropy  
- Epochs: 25  
- Validation Split: 0.2  
- Accuracy: ~97–98%

## Results
- Training accuracy: ~98%
- Validation accuracy: ~97%
- Correctly predicts unseen handwritten digits

## Visualization
Training loss, validation loss, and accuracy are plotted using Matplotlib.
