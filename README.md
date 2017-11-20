# Tensorflow Tutorial
Programming assignment from Week 3 of Andrew Ng's 2nd course of his Deep Learning Specialisation series: Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization


This little project first goes over a few tensorflow exercises and then guides you to build a neural network using tensorflow; by creating computational graphs and then running the graph.

The dataset we're working with is a subset of the SIGNS dataset.  
**Training set:** 1080 pictures (64 by 64 pixels) of signs representing numbers from 0 to 5 (180 pictures per number).
**Test set:** 120 pictures (64 by 64 pixels) of signs representing numbers from 0 to 5 (20 pictures per number).

Our goal is to build an algorithm capable of recognizing a sign with high accuracy. 
To do so, we build a tensorflow model as **LINEAR -> RELU -> LINEAR -> RELU -> LINEAR -> SOFTMAX**

The notebook walks you through:  
- Initializing the parameters
- Implementing forward propagation
- Computing the cost
- Implementing backward propagation
- Updating the parameters
- Building the model
- Plotting the cost
- Calculating the predictions
- Calculating train and test accuracy

Have fun!
