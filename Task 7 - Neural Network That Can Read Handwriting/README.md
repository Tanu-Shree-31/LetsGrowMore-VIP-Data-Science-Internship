# TASK 7 - DEVELOP A NEURAL NETWORK THAT CAN READ HANDWRITING (ADVANCED LEVEL)

![image](https://user-images.githubusercontent.com/69342524/130347856-34e57e33-905b-4d15-b515-08c23d62ae1f.png)

In this project, we will recognize handwritten characters, i.e, MNSIT Digits from 0-9. This we are going to achieve by modeling a neural network that will have to be trained over a dataset containing images of alphabets.

# Project Prerequisites
Below are the prerequisites for this project:

1. Python (3.9.6 used)
2. IDE (Jupyter used)

# Required frameworks are

1. Numpy 
2. Keras 
3. Tensorflow (Keras uses TensorFlow in backend and for some image preprocessing) (version 2.0.0)
4. Matplotlib 

# What is CNN?
CNN stands for Convolutional Neural Networks that are used to extract the features of the images using several layers of filters.

![image](https://user-images.githubusercontent.com/69342524/130348130-9f35e932-df24-406d-930c-f064e93f443c.png)

The convolution layers are generally followed by maxpool layers that are used to reduce the number of features extracted and ultimately the output of the maxpool and layers and convolution layers are flattened into a vector of single dimension and are given as an input to the Dense layer (The fully connected network).

# Model Evaluation

1. Without using hidden layers in neural network 
- Accuracy of 92.54% in training dataset
- Accuracy of 92.60% in validation test set
2. Simple neural network with 1 layer 
- Accuracy of 99.46% in training dataset
- Accuracy of 97.61% in validation test set
3. Simple neural network with 3 layers
- Accuracy of 99.35% in training dataset
- Accuracy of 98.17% in validation test set

# Conclusion
We have successfully developed Handwritten character recognition (Text Recognition) with Python, Tensorflow, and Machine Learning libraries.

Handwritten characters have been recognized with more than 98% test accuracy. This can be also further extended to identifying the handwritten characters of languages too.
