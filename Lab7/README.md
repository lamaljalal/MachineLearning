# Logistic Regression Assignment

## Overview

In this project, Logistic Regression was used to build a model that predicts whether a user will click on an advertisement (Clicked on Ad) based on several features.

---

## Dataset

The dataset used is `advertising.csv`, which includes the following features:

* Daily Time Spent on Site
* Age
* Area Income
* Daily Internet Usage
* Male
* Clicked on Ad (Target)

---

## Steps

### 1. Exploratory Data Analysis

The following steps were performed:

* Loaded the dataset using pandas
* Displayed the first few rows using head
* Checked dataset information using info
* Reviewed statistical summaries using describe

---

### 2. Visualization

Several visualizations were created to better understand the data:

* Histogram to analyze the distribution of age
* Jointplots to explore relationships between variables
* KDE plot for density estimation
* Pairplot to examine relationships between features and the target

---

### 3. Data Preparation

* Selected the independent variables (features)
* Defined the target variable
* Split the dataset into:

  * Training set (70%)
  * Testing set (30%)

---

### 4. Model Building

* Used Logistic Regression from the sklearn library
* Trained the model on the training data

---

### 5. Evaluation

* Generated predictions on the test data
* Evaluated the model using:

  * Classification Report
  * Confusion Matrix
  * Accuracy Score

---

## Results

The model achieved an accuracy of approximately 97%, indicating strong performance in predicting user behavior.

---

## Conclusion

The dataset was successfully analyzed and a classification model was built using Logistic Regression. The model performed well on the test data and demonstrated good predictive capability.

---

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
