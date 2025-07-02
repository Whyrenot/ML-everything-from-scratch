# Neural Network Modules Implementation
## This repository contains a Python implementation of various neural network modules similar to PyTorch's functionality. The code includes layers, activation functions, loss criterions, and optimizers necessary for building and training deep learning models.

## Layers
* Linear (Fully Connected): Implements a dense layer with optional bias

* Conv2d: 2D convolutional layer with padding

* MaxPool2d: 2D max pooling layer

* Flatten: Reshapes input for transition between convolutional and dense layers

* BatchNormalization: Normalizes layer inputs

* Dropout: Implements dropout regularization

* Sequential: Container for stacking layers

## Activation Functions
* ReLU

* LeakyReLU

* ELU

* SoftPlus

* SoftMax

* LogSoftMax

## Loss Functions
* MSE Criterion

* Negative Log Likelihood Criterion (both stable and unstable versions)

## Optimizers
* SGD with Momentum

* Adam
