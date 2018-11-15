# Reinforcement learning #

This is a collection of simple reinforcement learning projects for my course "Introduction to Artificial Intelligence".

## Random action agents ##

* Random action agent for cart pole

## Linear model for action selection ##

The notebooks implement a simple linear model using numpy. We compute the inner product between a weight vector and the state vector. The action is selected depending on whether this inner product is negative or non-negative. 

* Random search for linear model agent for cart pole
* Hill climbing search for linear model agent for cart pole (not better than random search for this particularly simple problem)
* Random search for liner model agent for mountain car

## Tabular Q-learning ##

The notebooks implement tabular q-learning using numpy.

* Tabular Q-learning for frozen lake
* Tabular Q-learning for taxi

## Simple linear model and convolutional neural network for recognizing hand-written digits ##

The first notebook implements a simple linear model for recognizing hand-written digits with TensorFlow. I want to briefly introduce neurals network and TensorFlow in the context of a simple task in supervised learning. 

Once you become more familiar with neural networks and TensorFlow, I will show how to use neural networks approximate q-values in reinforcement learning.

The second notebook implements a convolutional neural network for recognizing hand-written digits.

Note that this is going to be a very brief introduction to neural networks and TensorFlow. We are going to have an entire class on these topics next semester.

## Q-learning with shallow neural networks ##

The notebooks implement q-learning with neural networks using TensorFlow.

* Neural network Q-learning for cart pole 
* Neural network Q-learning for mountain car 
