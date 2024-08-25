# Perceptron (1958)
Ref: https://towardsdatascience.com/what-is-a-perceptron-basics-of-neural-networks-c4cfea20c590

## What is a Perceptron? – Basics of Neural Networks
### An overview of the history of perceptrons and how they work.
![Biological Neuron vs. Artificial Neural Network Source](resource/images/perceptron_vs_biological_neuron.png)
A single-layer perceptron is the basic unit of a neural network. A perceptron consists of input values, weights and a bias, a weighted sum and activation function.
![perceptron](resource/images/perceptron.png "perceptron")
Represented visually we see (where typically the bias is represented near the inputs),
![perceptron_1](resource/images/perceptron_1.png)
![perscepron formula](resource/images/perceptron_2.png)

Logistic Functions<br>
![ACTIATION](resource/images/perceptron_activation1.webp)[Logistical functions have the formula]

Image by Author
Where the graph looks like,
![ACTIVATION](resource/images/perceptron_activation2.webp)

## Acivation function
### Common Activation Functions
- Sigmoid: Maps the input to a value between 0 and 1. Useful for binary classification problems.
- Tanh: Maps the input to a value between -1 and 1. Zero-centered, often preferred over sigmoid.
- ReLU (Rectified Linear Unit): Returns the input if positive, otherwise returns 0. Computationally efficient and helps overcome the vanishing gradient problem.
- Leaky ReLU: A variant of ReLU that avoids the "dying ReLU" problem by having a small positive slope for negative inputs.
- Softmax: Used in the output layer for multi-class classification problems. Outputs a probability distribution over the classes.

## Separate Data
Image by Geek3 from WIKIMEDIA COMMONS. Reposed with changes made to x and y-axis and function.

Let’s also create a graph with two different categories of data represented with red and blue dots.
![categories of data](resource/images/perceptron_3.png)
we see that a perceptron can do basic classification using a decision boundary.
![categories of data](resource/images/perceptron_4.png)

If you are interested in creating your own perceptron check this video out!
[![categories of data](resource/images/perceptron_5.png)]
https://youtu.be/ntKn5TPHHAk?si=132WcjoIGP6y7q2P

## multilayer perceptrons
![multilayer](resource/images/perceptron_multilayer2.gif)
![multilayer](resource/images/perceptron_multilayer.gif)

**Note**:
A three layer neural network can represent any multivariate function. <br>
https://arxiv.org/abs/2012.03016 <br>
In 1987, Hecht-Nielsen showed that any continuous multivariate function can be implemented by a certain type three-layer neural network. This result was very much discussed in neural network literature. In this paper we prove that not only continuous functions but also all discontinuous functions can be implemented by such neural networks.

