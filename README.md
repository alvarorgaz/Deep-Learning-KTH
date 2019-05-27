# Deep Learning in Data Science (KTH DD2424)

**Author:**

I am Álvaro Orgaz Expósito, a data science student at KTH (Stockholm, Sweden) and a statistician from UPC-UB (Barcelona, Spain).

**Abstract:**

This repository contains the assignments (code + report) of the Deep Learning course in my master's degree in Data Science at KTH (Stockholm, Sweden). The data used is the CIFAR10 with 60.000 images of 10 possible labels. You can download the data of the survey at: https://www.cs.toronto.edu/~kriz/cifar.html.

- *Assignment 1*: Multi-linear classifier network (no hidden layer, SoftMax output activation, Cross Entropy loss plus L2 regularization) with vanilla mini-batch backpropagation (coded from scratch). Tricks implemented: decaying learning rate, Xavier weights initialization, shuffling data by epochs, ensemble of networks, Hinge loss.

- *Assignment 2*: 2-layer classifier network (1 hidden layer with ReLu activation, SoftMax output activation, Cross Entropy loss plus L2 regularization) with cyclical learning rates (CLR from [Smith, 2015]) mini-batch backpropagation (coded from scratch). Tricks implemented: ensemble networks by cycles, dropout regularization, parameters tuning (regularization and learning rate range).

- *Assignment 3*: k-layer classifier network (k-1 hidden layer with ReLu activation and Batch Normalization, SoftMax output activation, Cross Entropy loss plus L2 regularization) with cyclical learning rates (CLR from [Smith, 2015]) mini-batch backpropagation (coded from scratch). Tricks implemented: batch normalization, dropout regularization, data augmentation with geometric jitter to training images.

- *Assignment 4*: Recurrent neural network (one input layer and output layer both with as many nodes as characters in alphabet and SoftMax as output activation function, 1 hidden layer with tanh as activation function, Cross Entropy loss over a sequence of characters) trained to predict text from the book *The Goblet of Fire* by J.K. Rowling and tweets of Donald Trump. During the training, the target character of each character in the input sequence is its following character in the book.

**Code:**

The project has been developed in Python using Jupyter Notebook.
