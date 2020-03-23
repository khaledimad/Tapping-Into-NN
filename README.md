# Tapping-Into-NN

## Project Description

There is a large amount of experience that goes into building a neural network (NN) to solve a classification / regression problem. In this exercise, we will be following the steps from a very well-articulated tutorial to build a NN. This NN can be used to identify hand-written digits. The model will be trained against labelled images of hand-written digits and the accuracy for the assigned test set will be calculated.

The tutorial can be found at: https://www.digitalocean.com/community/tutorials/how-to-build-a-neural-network-to-recognize-handwritten-digits-with-tensorflow.

## First model accuracy
Based on our model, we evaluate a test accuracy of approximately 91.1% for data points ranging from 3301 to 6600.

## Second model accuracy (no dropouts)
After removing the dropouts from the final layer, we notice an improvement in the model with a
newly observed accuracy of 91.5%.
<br>Dropouts are used in Neural networks to avoid overfitting during the training phase. In a fully
connected network, the neurons develop dependency between each other which leads to overfitting
of the training dataset.
<br>Dropouts are similar to regularization in regression. Probabilistically dropping out neuron in the
network is a simple and effective regularization method. This explains why the accuracy has
increased when we removed the dropouts from the neural net model. IT has increased since the
neural net overfitted on the training data.

## Other conventional algorithms
One possible alternative would be K-Nearest Neighbors. While the K-NN method is considered
simpler due to the fact that it only requires adjusting one hyperparameter (k-value), using a neural
network comes at its own advantages:<br>
1. It can significantly outperform other algorithms in the right conditions (this comes at a
cost of time).<br>
2. Learning can be transferred to other similar tasks based on its established parameters.<br>
3. Performs well in a high-dimensional space.<br>

## Multinomial logistic regression model
After applying multinomial logistic regression for the same testing dataset, we obtained a model with an out of sample accuracy of 92.2% which is higher than that obtained from the neural network exercises earlier.
