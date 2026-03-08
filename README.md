# Custom Neural Network Engine (From Scratch)

This project implements a fully customizable neural network engine built from scratch using NumPy.

No TensorFlow.  
No PyTorch.

The goal of this project is to understand the internal mechanics of neural networks including forward propagation, activation functions, and backpropagation.

## Features

- Custom neural network architecture
- Dynamic hidden layers
- ReLU activation for hidden layers
- Softmax output layer
- Stochastic Gradient Descent (SGD)
- Implemented entirely using NumPy

## Experiment

Dataset: MNIST Handwritten Digits

Training Images: 2000  
Testing Images: 1000  
Epochs: 30  

Accuracy Achieved: *~91%*

Despite training on *less than 3% of the MNIST dataset*, the model performs strongly.

Increasing the training dataset to *20k–30k samples* is expected to push accuracy *above 97%*.

## Motivation

The goal of this project was to understand neural networks at a deeper level by implementing them from scratch instead of relying on deep learning frameworks.

## Notebook

The full implementation and experiments can be found in:

neural_network_from_scratch.ipynb
