# Deep Learning in Data Science (KTH DD2424)

**Author:**

I am Álvaro Orgaz Expósito, a data science student at KTH (Stockholm, Sweden) and a statistician from UPC-UB (Barcelona, Spain).

**Abstract:**

This repository contains the assignments (code + report) of the Deep Learning course in my master's degree in Data Science at KTH (Stockholm, Sweden). The data used is the CIFAR10 with 60.000 images of 10 possible labels. You can download the data of the survey at: https://www.cs.toronto.edu/~kriz/cifar.html.

- *Assignment 1*: Multi-linear classifier network (no hidden layer, SoftMax output activation, Cross Entropy loss plus L2 regularization) with vanilla mini-batch backpropagation (coded from scratch). Tricks implemented: decaying learning rate, Xavier weights initialization, shuffling data by epochs, ensemble of networks, Hinge loss.

- *Assignment 2*: 2-layer classifier network (1 hidden layer with ReLu activation, SoftMax output activation, Cross Entropy loss plus L2 regularization) with cyclical learning rates (CLR from [Smith, 2015]) mini-batch backpropagation (coded from scratch). Tricks implemented: ensemble networks by cycles, dropout regularization, parameters tuning ($\lambda$ and $\eta$ range).

**Code:**

The project has been developed in Python using Jupyter Notebook.
