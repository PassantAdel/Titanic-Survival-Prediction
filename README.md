# Titanic-Survival-Prediction
This repository contains a Python script for predicting survival on the Titanic using a Random Forest Classifier. 
The script utilizes the pandas and scikit-learn libraries for data manipulation and machine learning.

## Dataset
The dataset used for training and testing the model is loaded from CSV files named "train.csv" and "test.csv."

## Problem Statement
The goal is to predict whether a passenger survived or not based on the given features. 
The script demonstrates the process of exploring the data, training a Random Forest model, and generating predictions.

## Dependencies
Make sure you have the required dependencies installed. You can install them using the following:
pip install pandas.
pip install scikit-learn.

## Steps  

1. Loads and explores the training and testing datasets.
2. Calculates and prints the percentage of survived women and men.
3. Prepares the data by selecting relevant features and one-hot encoding categorical variables.
4. Trains a Random Forest model and generates predictions.
5. Saves the predictions to CSV files named "submission.csv" and "submission2.csv" based on different feature sets.
