# digit-classifier-from-scratch
This project implements a digit classifier from scratch using NumPy, without relying on deep learning frameworks. The model is a simple 2-layer neural network trained on the MNIST handwritten digits dataset.
The goal of this project is to demonstrate a clear understanding of:
- Neural network fundamentals
- Forward and backward propagation
- Gradient descent optimization
- Classification using softmax

# Model Overview
- Input layer: 784 neurons (28×28 pixel images flattened)
- Hidden layer: 10 neurons with ReLU activation
- Output layer: 10 neurons with Softmax activation (digits 0–9)
# Key Components Implemented
He initialization for weights
ReLU activation and derivative
Softmax output layer
Cross-entropy loss (via softmax gradient)
Backpropagation
Gradient descent parameter updates
Accuracy evaluation

# Dependencies
This project only requires the following Python libraries:
`pip install numpy matplotlib´

# MNIST Dataset Setup
Included in the repo there is a file called `mnist_datareader.py` using this you can simply download the dataset from https://www.kaggle.com/datasets/hojjatk/mnist-dataset and and these files in a folder called input. The mnist_datareader is imported in the main file and will read the dataset.

