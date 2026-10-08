Machine Learning Concepts

This repository contains my learning and practice work on fundamental
Machine Learning concepts, starting from data processing and progressing
through basic regression algorithms.

Topics Covered

1. Data Processing

Loading datasets

Understanding the dataset

Basic data cleaning

Handling missing values

Selecting features and target variables

Basic data visualization

Preparing data for Machine Learning

2. Linear Regression

Linear Regression is a supervised learning algorithm used to predict a
continuous numerical value.

Basic idea:

y = mx + c

Where: - x = input feature - y = predicted output - m =
slope/coefficient - c = intercept

Example: Predicting house price based on area.

3. Polynomial Regression

Polynomial Regression is an extension of Linear Regression that is
useful when the relationship between the input and output is curved
rather than a straight line.

General form:

y = b0 + b1x + b2x² + ... + bnxⁿ

Example: Predicting a value when the relationship between the
feature and target is non-linear.

4. Multiple Linear Regression

Multiple Linear Regression is used when the target value depends on two
or more input features.

General form:

y = b0 + b1x1 + b2x2 + ... + bnxn

Where: - y = predicted output - x1, x2, ..., xn = input features -
b0 = intercept - b1, b2, ..., bn = coefficients

Example: Predicting house price using area, number of bedrooms,
location-related features, and age of the house.

Repository Structure

Data_processing/
│
├── Day1-4_Kaggle_Notebook.ipynb
├── regression-notebook (1).ipynb
├── dataset.csv
└── README.md

Learning Progress

Data Processing

Linear Regression

Polynomial Regression

Multiple Linear Regression

Tools & Technologies

Python

NumPy

Pandas

Matplotlib

Scikit-learn

# Logistic Regression - Course Completion Prediction

## Overview

This project implements Logistic Regression to predict whether a student will complete an online course based on their learning activity and quiz performance.

The model predicts two possible outcomes:

- `1` → Student completed the course
- `0` → Student did not complete the course

## Dataset

The dataset used in this project is `course_completion.csv`.

### Features

The model uses the following features:

- `hours_per_week` - Number of hours spent learning per week
- `logins_count` - Number of times the student logged into the course
- `quiz_avg_score` - Average quiz score of the student

### Target Variable

- `completed`

Where:

- `1` = Completed
- `0` = Not Completed

## Machine Learning Approach

The project demonstrates Logistic Regression both from scratch and using Scikit-learn.

### Logistic Regression from Scratch

The implementation includes:

1. Loading the dataset
2. Selecting features and target
3. Train-test splitting
4. Feature scaling
5. Sigmoid function
6. Probability calculation
7. Log Loss / Cross-Entropy Loss
8. Gradient Descent
9. Weight and bias updates
10. Making predictions
11. Evaluating the model

### Workflow

```text
Dataset
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Linear Score
   ↓
Sigmoid Function
   ↓
Probability
   ↓
Log Loss
   ↓
Gradient Descent
   ↓
Update Weights and Bias
   ↓
Prediction
   ↓
Model Evaluation