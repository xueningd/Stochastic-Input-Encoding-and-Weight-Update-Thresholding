# Stochastic-Input-Encoding-and-Weight-Update-Thresholding
Stochastic Input Encoding and Weight Update Thresholding for Efficient Memristive Neural Network In-Situ Training

## Getting started
All code blocks in the .ipynb files need to be run sequentially to obtain the results.

The Sentimental Analysis dataset is a Twitter message dataset that can be found at [Sentimental Analysis](http://www.sentiment140.com/), created by Stanford.

## Contents
- [MNIST_CNN_insitu.ipynb](../main/MNIST_CNN_insitu.ipynb) contains the code for training a simple CNN model on the MNIST dataset using the passive crossbar model. All three proposed methods (SGD-only, thresholded update and Manhattan learning rule) are implemented.
- [CIFAR10_CNN_insitu.ipynb](../main/CIFAR10_CNN_insitu.ipynb) contains the code for training a ResNet-18 model on the CIFAR-10 dataset using the passive crossbar model. All three proposed methods (SGD-only, thresholded update and Manhattan learning rule) are implemented.
- [RNN_sentimental_insitu.ipynb](../main/RNN_sentimental_in_situ.ipynb) contains the code for training a simple RNN model on the Sentimental Analysis dataset using the passive crossbar model. All three proposed methods (SGD-only, thresholded update and Manhattan learning rule) are implemented.
- [ex_situ_error.ipynb](../main/ex_situ_error.ipynb) contains training code for above three models using PyTorch. Results are used for comparison with the above in-situ training models.
