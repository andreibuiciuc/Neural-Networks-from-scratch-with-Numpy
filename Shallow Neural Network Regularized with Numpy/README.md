### Shallow Neural Network Classifier implemented with Numpy ###

In this notebook, a shallow neural network (with only one hidden layer) is built from scratch using numpy. The goal for this problem is to correctly classify points in a planar setting.

<p align="center">
  <img src="https://user-images.githubusercontent.com/88616177/134171168-571f5a15-b6a1-41fd-9032-b82bff29d2b4.png">
</p>

To reduce the amount of overfitting, L2 regularization (Frobenius Norm) was used. The effects on how the model behaves with or without regularization can be seen in the images below (tested on a model with 8 units in the hidden layer, a lambda coefficient <<from L2 regularization formula>> of 0.7 and a learning rate of 0.3). 

Without regularization: 

<p align="left">
  <img src="https://user-images.githubusercontent.com/88616177/134173304-c2963935-24da-449e-a12f-701499fd3626.png">
</p>

With regularization:

<p align="left">
  <img src="https://user-images.githubusercontent.com/88616177/134173387-b756f1d7-42d8-42b7-9833-4f6f7c543c2e.png">
</p>

Depending on the planar dataset used and its degree of linearly separability, the model can reach an accuracy higher than 90% (more or less).
