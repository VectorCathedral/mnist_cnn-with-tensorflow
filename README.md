# Handwritten Digit Recognition using Neural Networks (MNIST)

This project builds and trains a feedforward neural network using TensorFlow and Keras to recognize handwritten digits (0–9) from the MNIST dataset.
It demonstrates the essential steps of building, training, and evaluating a neural network for image classification.

## 📘 Overview

The MNIST dataset is a classic benchmark in machine learning, consisting of 70,000 grayscale images of handwritten digits:

60,000 for training

10,000 for testing
Each image is 28×28 pixels in size.

The model in this project:

Flattens each image into a 1D array (784 features)

Passes it through two hidden layers with ReLU activation

Outputs probabilities for each of the 10 digit classes using Softmax

## 🧠 Model Architecture
Layer	Type	Units	Activation	Description
Input	Flatten	—	—	Converts 28×28 images into 1D arrays
Hidden 1	Dense	128	ReLU	Learns low-level features (edges, curves)
Hidden 2	Dense	128	ReLU	Learns higher-level features (shapes, digit structure)
Output	Dense	10	Softmax	Predicts probability distribution over 10 digits
⚙️ Dependencies

Make sure you have the following installed:

pip install tensorflow numpy matplotlib


## 🧩 Key Features

Demonstrates the entire workflow: data loading, normalization, model building, training, and evaluation

Uses ReLU and Softmax activation functions

Implements a fully connected neural network architecture

Easily extendable — try adding convolutional layers for higher accuracy

## 🧾 License

This project is open-source and available under the MIT License
