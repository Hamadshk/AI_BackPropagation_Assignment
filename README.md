# 🔬 AI Backpropagation Assignment

This project implements a customizable neural network with backpropagation for solving the XOR problem. The neural network is designed to be flexible, allowing the user to define the number of hidden layers and the number of neurons in each layer.

## 🚀 Features

- Input size: 2
- Output size: 1
- Random weight initialization
- Dynamic hidden layers and neurons as specified by the user
- Sigmoid activation function
- Feedforward process for output computation
- Backpropagation algorithm for updating weights and biases
- Learning rate (eta) for weight and bias updates
- Training using the XOR problem dataset
- User inputs for:
    - Number of hidden layers
    - Number of neurons in each hidden layer
    - Number of iterations for training
- Output, weights, and biases printed after each iteration during training

## 📊 XOR Problem Dataset

The XOR problem is a fundamental problem in neural network training. The correct outputs for XOR are as follows:


## 🔧 Implementation Details

The implementation includes the following steps:

### 1. Random Weight Initialization 🌟

Weights are initialized randomly to ensure the network starts with a diverse range of weights.

### 2. Dynamic Hidden Layers and Neurons 🔄

The network structure can be customized by specifying the number of hidden layers and the number of neurons in each hidden layer at runtime.

### 3. Sigmoid Activation Function 📈

The sigmoid function is used as the activation function for neurons in the network.

### 4. Feedforward Process 🚀

The feedforward process computes the output of each layer based on the inputs and the weights.

### 5. Backpropagation Algorithm 🔙

The backpropagation algorithm is used to update the weights and biases based on the error at the output layer.

### 6. Learning Rate (Eta) ⚙️

The learning rate determines the step size for updating the weights and biases during training.

### 7. Training with XOR Dataset 🧠

The network is trained using the XOR dataset, and the output, weights, and biases are printed after each iteration.

## ⚙️ User Inputs

The user can provide the following inputs:

- Number of hidden layers
- Number of neurons in each hidden layer
- Number of iterations for training

## 🎉 Happy Training!

With this implementation, you can explore and understand the inner workings of a neural network and its training process using backpropagation.
