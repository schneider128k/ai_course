# Artificial intelligence

I taught a course on artificial intelligence in Fall 2018.

I used the materials (slides and programming assignments) from [UC Berkeley CS188 Intro to AI](http://ai.berkeley.edu/home.html). 
Using these materials, I covered the following topics:
- Uninformed search
- Informed search
- Adverseral search
- Expectimax search
- Markov decision processes
- Reinforcement learning

At the end of the semester, I introduced [OpenAI gym](https://gym.openai.com/) and showed the students how to solve 
- simple environments such as frozen late and taxi using tabular q-learning and 
- cartpole and mountain car using q-learning combined with very simple neural networks and an experience reply buffer. I also showed students how to use dense and convolution neural network for recognizing digits in the MNIST data set. The code for this part of the course is contained in this repo.

---

## Reinforcement learning #

This is a collection of simple reinforcement learning projects for my course CAP 5636 Advanced Artificial Intelligence in Fall 2018.

### Taxonomy of reinforcement learning methods ##
https://github.com/schneider128k/reinforcement/blob/master/taxonomy_rl_methods.md

### Random action agents ##

* Random action agent for cart pole

### Linear model for action selection ##

The notebooks implement a simple linear model using numpy. We compute the inner product between a weight vector and the state vector. The action is selected depending on whether this inner product is negative or non-negative. 

* Random search for linear model agent for cart pole
* Hill climbing search for linear model agent for cart pole (not better than random search for this particularly simple problem)
* Random search for liner model agent for mountain car

### Tabular Q-learning ##

The notebooks implement tabular q-learning using numpy.

* Tabular Q-learning for frozen lake
* Tabular Q-learning for taxi

### Simple linear model and convolutional neural network for recognizing hand-written digits ##

The first notebook implements a simple linear model for recognizing hand-written digits in the MNIST data set with TensorFlow. I want to briefly introduce neurals networks and TensorFlow in the context of this basic task in supervised learning.  

Once we become more familiar with neural networks and TensorFlow, I will show how to use neural networks to approximate q-values for simple reinforcement learning tasks such as cartpole and mountain car.

The second notebook implements a convolutional neural network for recognizing hand-written digits. We need to use convolutional neural networks to approximate q-values for more advanced tasks such as playing Atari games.

Note that this is going to be a very brief introduction to neural networks and TensorFlow. I am going to be teaching an entire class on deep neural networks and TensorFlow in Spring 2019.

### Cross entropy method policy learning ##

* Cross entropy method policy learning for cart pole

### Q-learning with shallow neural networks ##

The notebooks implement q-learning with neural networks using TensorFlow.

* Neural network Q-learning for cart pole 
* Neural network Q-learning for mountain car 
