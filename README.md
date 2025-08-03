# Titanic Data Science Project

## Overview
Data analysis and machine learning project on the Titanic dataset. This project has two main parts:
- Exploratory Data Analysis of the Titanic dataset to discover patterns and find factors that effect the survival chance.
- Training a Machine Learning model to predict the chance of survival for any given passenger.

## Exploratory Data Analysis (EDA)
- File: data/eda.ipynb
- This part of the project contains the cleanup and anaylsis of the Titanic dataset.

## Machine Learning
- File: model/model.ipynb
- This part of the project is focused on training a neural network to predict survival chances of Titanic passengers.
- The model consist of 3 layers: An input layer, a hidden layer and an output layer.
- Each layer has ReLU and BatchNorm funtions.
- The output is later passed onto the sigmoid function to calculate the final result.
- I used binary crossentropy as loss funtion and Adam as optimizer.
- The model can achieve up to 85% accuracy on the validation dataset.

## Libraries Used
- Pandas, Numpy, Matplotlib and Seaborn for data analysis and visualization
- Pytorch (mainly) and Sklearn (for setting up data) for model training.