# Handwritten Digit Recognition Using a Neural Network from Scratch

## Overview

This project is a neural network built entirely from scratch using NumPy to classify handwritten digits from the MNIST dataset.

The main goal was not just to achieve good accuracy, but to understand how neural networks actually work under the hood. Instead of using frameworks such as TensorFlow or PyTorch, every major component of the network was implemented manually, including forward propagation, backpropagation, softmax activation, and gradient descent.

The model learns to recognize handwritten digits from 0 to 9 based on pixel values from grayscale images.

---

## Dataset

The project uses the MNIST Handwritten Digit Dataset.

* 60,000 training images
* 10,000 test images
* 10 classes (digits 0-9)
* Image size: 28 × 28 pixels
* 784 input features per image

MNIST is one of the most widely used datasets for learning image classification and neural networks.

---

## Neural Network Architecture

Input Layer: 784 neurons

↓

Hidden Layer: 10 neurons with ReLU activation

↓

Output Layer: 10 neurons with Softmax activation

---

## Features Implemented

The following components were implemented from scratch using NumPy:

* Parameter initialization
* One-hot encoding
* Forward propagation
* ReLU activation
* Softmax activation
* Backpropagation
* Gradient descent optimization
* Prediction pipeline
* Multi-class classification

No deep learning frameworks were used.

---

## Results

| Metric            | Accuracy |
| ----------------- | -------- |
| Training Accuracy | 93.49%   |
| Test Accuracy     | 92.85%   |

The small difference between training and test accuracy suggests that the model generalizes well to unseen handwritten digits and does not suffer from significant overfitting.

---

## What I Learned

Building this project helped me understand:

* How neural networks process information layer by layer
* The mathematics behind backpropagation
* How gradients are used to update parameters
* The role of activation functions such as ReLU and Softmax
* One-hot encoding for multi-class classification
* The importance of evaluating performance on unseen data

More importantly, it helped me move beyond simply using machine learning libraries and understand the mechanics behind them.

---

## Technologies Used

* Python
* NumPy
* Pandas

---

## Future Improvements

Some possible improvements include:

* Adding additional hidden layers
* Experimenting with different activation functions
* Implementing mini-batch gradient descent
* Implementing Adam optimization
* Building a Convolutional Neural Network (CNN)
* Creating a simple web interface for digit prediction

---

## Author

Yash Mittal

Built as part of my journey to understand neural networks and machine learning from first principles.
