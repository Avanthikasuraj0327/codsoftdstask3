# codsoftdstask3

# Iris Flower Classification

This project uses the Iris flower dataset to develop a machine learning model that can classify iris flowers into different species based on their sepal and petal measurements. The Iris dataset is widely used for introductory classification tasks.

## Table of Contents

- [Description](#description)
- [Dataset](#dataset)
- [Usage](#usage)
- [Model](#model)
- [Results](#results)
  
## Description

The objective of this project is to train a machine learning model that can accurately classify iris flowers into their respective species (setosa, versicolor, and virginica) based on their sepal and petal measurements.

## Dataset

The dataset used in this project is the Iris dataset, which consists of 150 samples from three species of Iris flowers:
- Iris setosa
- Iris versicolor
- Iris virginica

Each sample contains the following measurements:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

## Model
The project uses a Logistic Regression model to classify the iris flowers. The model is trained using the sepal and petal measurements from the dataset.

## Results
The Logistic Regression model achieved an accuracy of 100% on the test set. Below is the detailed classification report:

              precision    recall  f1-score   support

      setosa       1.00      1.00      1.00        19
  versicolor       1.00      1.00      1.00        13
   virginica       1.00      1.00      1.00        13
    accuracy                           1.00        45
   macro avg       1.00      1.00      1.00        45
weighted avg       1.00      1.00      1.00        45
