# 🧠 SVM Assignment – Breast Cancer Classification

A machine learning project that applies the **Support Vector Machine (SVM)** algorithm to classify breast cancer tumors as **malignant** or **benign** using the Breast Cancer Wisconsin dataset from Scikit-learn.

---

## 📌 Project Overview

This notebook demonstrates the complete workflow of building a machine learning classification model, including:

- Data loading
- Exploratory Data Analysis (EDA)
- Data visualization
- Training an SVM classifier
- Model evaluation
- Hyperparameter tuning using GridSearchCV

---

## 📂 Dataset

The dataset used is the **Breast Cancer Wisconsin Dataset** available in Scikit-learn.

### 🎯 Target Classes

| Label | Class |
|------|------|
| 0 | Malignant |
| 1 | Benign |

---

## 🛠️ Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## ⚙️ Project Workflow

### 1️⃣ Import Required Libraries

Imported all libraries needed for:
- Data analysis
- Data visualization
- Machine learning

---

### 2️⃣ Load the Dataset

```python
from sklearn.datasets import load_breast_cancer
```

Loaded the dataset and converted it into a Pandas DataFrame for easier analysis.

---

### 3️⃣ Exploratory Data Analysis (EDA)

Performed data exploration using:
- `.info()`
- `.describe()`
- Pairplots
- KDE plots

This helped visualize relationships between features and understand the dataset structure.

---

### 4️⃣ Split the Data

Used `train_test_split()` to divide the dataset into:
- Training data
- Testing data

---

### 5️⃣ Train the SVM Model

```python
from sklearn.svm import SVC
```

Created and trained an SVM classifier on the training dataset.

---

### 6️⃣ Evaluate the Model

Model performance was evaluated using:
- Confusion Matrix
- Classification Report
- Accuracy Score

---

### 7️⃣ Hyperparameter Tuning

Used `GridSearchCV` to optimize:
- `C`
- `gamma`

This improved the model performance and selected the best parameters automatically.

---

## ✅ Results

- Model Accuracy: **~98%**
- The optimized SVM model achieved excellent classification performance.

---

## ▶️ How to Run

### Clone the repository

```bash
git clone <repository-link>
```

### Open the notebook

```bash
02-SVM Assignment - Solved.ipynb
```

### Run all notebook cells sequentially

---

## 📁 Project Structure

```bash
├── 02-SVM Assignment - Solved.ipynb
└── README.md
```

---

## 👨‍💻 Author

Machine Learning Lab – SVM Assignment
