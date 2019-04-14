# Deep-Learning

https://www.cs.toronto.edu/~kriz/cifar.html



Deep-Learning
This is a repo for the individual course assignments of DD2424 Deep Learning in Data Science at KTH 2017. The code in this repo is mainly done in Matlab, and manipulations involved in the training process like gradient calculations and parameter updates are implemented in a trival way (low level).

Datasets
CIFAR-10 for assignment 1-3

The Goblet of Fire and Trump Tweets for assignment 4

Contents
Assignment 1: one-layer network with multiple-class outputs (test accuracy: 40.42%)

report: basic + optional

Assignment 2: two-layer network with multiple-class outputs (test accuracy: 54.06%)

report: basic + optional

Assignment 3: k-layer network with multiple-class outputs (test accuracy: 54.8%)

report: basic + optional

Assignment 4: vanilla RNN to synthesize English text character by character

report: basic + optional



Research-on-Feature-Importance-for-Stacking-Models
Author:

I am Álvaro Orgaz Expósito, a data science student at KTH (Stockholm, Sweden) and a statistician from UPC-UB (Barcelona, Spain).

Abstract:

This repository contains the final project of the Research Methodology and Scientific Writing course in my master's degree in Data Science at KTH (Stockholm, Sweden).

Have you ever sought treatment for a mental health issue from a mental health professional? This project answers this question using state of the art Machine Learning. Check your results at http://141.223.239.241:1234/mentalchecker/

The data used is a survey on mental health in the tech workplace known as OSMI Mental Health in Tech Survey available at Kaggle. It has 2692 responses in total (2014 and 2016) for asked questions that aimed to measure attitudes to mental health in the tech workplace and examine the frequency of mental disorders among tech workers. You can download the data of the survey at:

2014 at https://www.kaggle.com/osmi/mental-health-in-tech-survey
2016 at https://www.kaggle.com/osmi/mental-health-in-tech-2016
The main aims of this project are:

Predict the probability of receiving treatment for a mental health issue from a mental health professional
Use the ensembling technique Stacking for combining Supervised Machine Learning models such as: Logistic Regression, Random Forest, K Nearest Neighbors, ExtraTrees, XGBoost, LGBM, Decision Tree, AdaBoost
Explain the prediction of Stacking model for a new person that answers the survey using statistics on original survey data
Provide a feature importance and instability measure for Stacking models
Files in main folder:

Jupyter Notebook files with the code of the project
Data folder with data and outputs of the code:
Data2014.csv contains the survey data of 2014
Data2016.csv contains the survey data of 2016
data.dat contains preprocessed survey data (without normalization and one hot encoding)
data_splits.dat contains preprocessed survey data split in train, validation and test (with normalization and one hot encoding)
preprocessing_dictionaries.dat contains preprocessing information of missings imputation, normalization and one hot encoding
model_layer1_.dat files contain 1st stacking layer models
model_layer2_metalearner.dat file contains 2nd stacking layer model or metalearner
Code:

The project has been developed in Python using Jupyter Notebook.
