SVM Assignment - Breast Cancer Classification
📌 Overview

This project demonstrates the implementation of a Support Vector Machine (SVM) model for breast cancer classification using the Breast Cancer dataset provided by Scikit-learn.

The notebook covers:

Data exploration and visualization
Data preprocessing
Training an SVM classifier
Model evaluation
Hyperparameter tuning using GridSearchCV
📂 Dataset

The dataset used is the Breast Cancer Wisconsin Dataset from sklearn.datasets.

Features include:
Radius
Texture
Perimeter
Area
Smoothness
Compactness
Concavity
Symmetry
Target Classes
Label	Meaning
0	Malignant
1	Benign
🛠️ Technologies & Libraries
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
📊 Project Workflow
1️⃣ Import Libraries

Imported all required libraries for:

Data analysis
Visualization
Machine learning
2️⃣ Load Dataset

Loaded the Breast Cancer dataset using:

from sklearn.datasets import load_breast_cancer
3️⃣ Exploratory Data Analysis (EDA)

Performed data exploration and visualization using:

Pairplot
KDE plots
Dataset information and statistics
4️⃣ Train/Test Split

Split the dataset into training and testing sets using:

train_test_split()
5️⃣ Train SVM Model

Built and trained an SVM classifier using:

from sklearn.svm import SVC
6️⃣ Model Evaluation

Evaluated model performance using:

Confusion Matrix
Classification Report
Accuracy Score
7️⃣ Hyperparameter Tuning

Optimized the model using:

GridSearchCV

Tuned parameters:

C
gamma
✅ Results
Achieved approximately 98% accuracy
GridSearchCV produced optimized parameters with very high performance
▶️ How to Run
Clone the repository
git clone <your-repository-link>
Open the notebook
02-SVM Assignment - Solved.ipynb
Run all cells

Execute all notebook cells sequentially.

📁 Project Structure
├── 02-SVM Assignment - Solved.ipynb
├── README.md
👨‍💻 Author

Machine Learning Lab — SVM Assignment
