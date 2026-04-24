# Decision Trees and Random Forest Project

## Overview

This project applies machine learning techniques using Decision Trees and Random Forests to predict whether a loan will be fully paid or not.

## Dataset

The dataset used in this project is `loan_data.csv`. It contains financial information about borrowers, including:

* credit.policy
* purpose
* int.rate
* installment
* log.annual.inc
* dti
* fico
* days.with.cr.line
* revol.bal
* revol.util
* inq.last.6mths
* delinq.2yrs
* pub.rec
* not.fully.paid (Target)

## Objective

The goal is to build classification models to predict the variable `not.fully.paid`.

## Steps

### 1. Data Exploration

* Load dataset using pandas
* Explore structure using info(), head(), and describe()
* Visualize relationships using matplotlib and seaborn

### 2. Data Preprocessing

* Convert categorical variable `purpose` into dummy variables
* Prepare feature matrix (X) and target vector (y)

### 3. Train-Test Split

* Split the dataset into training and testing sets using sklearn

### 4. Model Training

#### Decision Tree

* Train a Decision Tree Classifier
* Generate predictions on test data

#### Random Forest

* Train a Random Forest Classifier
* Generate predictions on test data

### 5. Evaluation

* Use classification report
* Use confusion matrix
* Compare performance between models

## Results

Random Forest generally performs better than Decision Tree due to ensemble learning, which reduces overfitting and improves accuracy.

## Libraries Used

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

## How to Run

1. Make sure Python is installed
2. Install required libraries:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the notebook or Python script

## Author

Lama
