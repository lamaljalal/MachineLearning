# K-Nearest Neighbors (KNN) Project

## Overview

This project implements the K-Nearest Neighbors (KNN) algorithm using Python and Scikit-learn. The objective is to classify data points based on the similarity to their nearest neighbors.

## Dataset

The dataset used is `KNN_Project_Data`, which contains multiple features used to predict the target class.

## Project Steps

### 1. Import Libraries

The following libraries are used:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

### 2. Exploratory Data Analysis (EDA)

* Display dataset structure using `head()`
* Visualize relationships using `pairplot`

### 3. Data Preprocessing

* Separate features (X) and target (y)
* Apply feature scaling using `StandardScaler`

### 4. Train-Test Split

The dataset is split into training and testing sets to evaluate model performance.

### 5. Model Training

The KNN model is built using:

* `KNeighborsClassifier`

### 6. Model Evaluation

Performance is evaluated using:

* Confusion Matrix
* Classification Report

### 7. Choosing Optimal K

* Use the Elbow Method to find the best value of K
* Plot error rate against different K values

## Results

The model performance improves after selecting an optimal value of K based on the error rate.

## How to Run

1. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

2. Run Jupyter Notebook:

```bash
jupyter notebook
```

3. Open the file:

```
Lab8.ipynb
```

## Notes

* Feature scaling is essential for KNN performance
* The choice of K significantly affects the results
