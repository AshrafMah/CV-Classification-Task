# Fashion-MNIST CNN Classification with PyTorch

## Overview
This project implements a Convolutional Neural Network (CNN) using the LeNet-5 architecture to classify images from the Fashion-MNIST dataset. The aim is to compare the performance of the CNN with different optimizers, activation functions, pooling techniques, and the use of data augmentation and dropout.

## Objectives
The main objectives of this project are to:
1. Implement a CNN for the image classification problem using the Fashion-MNIST dataset.
2. Compare the performance of the CNN with:
    - Different optimizers: Stochastic Gradient Descent (SGD), RMSprop, and Adam.
    - Different activation functions: Sigmoid, Tanh, and ReLU.
    - Different pooling functions: Max pooling and average pooling.
    - Dropout (probability=0.5) versus no dropout.
    - Data augmentation versus no data augmentation.

## Dataset
Fashion-MNIST is a dataset of Zalando's article images consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image associated with a label from 10 classes.

## Experimental Setup
1. **Experiment 1**: Compare different activation functions (Tanh, Sigmoid, and ReLU).
2. **Experiment 2**: Compare different pooling techniques (Max pooling and average pooling).
3. **Experiment 3**: Evaluate different optimization algorithms (SGD, Adam, and RMSprop).
4. **Experiment 4**: Assess the impact of dropout.
5. **Experiment 5**: Assess the impact of data augmentation.
