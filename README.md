# CSNN-MNIST
This is a project on classification of data in the MNIST dataset using Convolutional Spiking Neural Network with the help of surrogate gradient descent . 
The model has achieved 93.07\% accuracy on the test set (final cross-entropy loss: 7.93) after training on 60,000 MNIST images (batch size: 128).
This training employed surrogate gradient descent, utilizing the non-differentiable Heaviside step function in the forward pass to model neuron firing and the differentiable Arctangent function in the backward pass to enable gradient computation.
