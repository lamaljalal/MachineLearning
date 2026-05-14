# Credit Card Customer Segmentation

This project applies K-Means Clustering on credit card customer data to identify different customer segments based on customer spending behavior, balance, purchases, and cash advance usage.

---

## Dataset

The dataset used in this project is:

- CC_GENERAL.csv

The dataset contains customer information such as:
- Balance
- Purchases
- Credit Limit
- Cash Advance
- Payment Behavior
- Installment Purchases

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Project Steps

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Scaling
5. Finding Optimal Number of Clusters
6. K-Means Clustering
7. PCA Visualization
8. Cluster Analysis

---

## Data Preprocessing

- Removed the `CUST_ID` column
- Filled missing values using mean values
- Standardized features using `StandardScaler`

---

## Clustering Method

This project uses:

- K-Means Clustering

To determine the best number of clusters:
- Elbow Method
- Silhouette Score

Final selected number of clusters:

K = 4

---

## Results

The model successfully divided customers into different groups such as:

- High-value customers
- Low-activity customers
- Customers with high cash advance usage
- Moderate spending customers

---

## Visualization

PCA was used to reduce dimensions and visualize customer segments in 2D space.

---

## How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
