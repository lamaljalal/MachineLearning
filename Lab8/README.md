# K-Nearest Neighbors (KNN) Project

## 📌 Overview

This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** algorithm using Python and Scikit-learn.
The goal is to classify data points based on their nearest neighbors.

---

## 📊 Dataset

The dataset used in this project is **KNN_Project_Data**, which contains several features used to predict the target class.

---

## ⚙️ خطوات العمل

### 1. استيراد المكتبات

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

### 2. استكشاف البيانات (EDA)

* عرض البيانات باستخدام `head()`
* رسم العلاقات باستخدام `pairplot`

---

### 3. تجهيز البيانات

* فصل البيانات إلى:

  * Features (X)
  * Target (y)
* تطبيق **StandardScaler** لتوحيد القيم

---

### 4. تقسيم البيانات

تم تقسيم البيانات إلى:

* Training set
* Testing set

---

### 5. بناء النموذج

استخدام خوارزمية:

* **KNeighborsClassifier**

---

### 6. التقييم

تم استخدام:

* Confusion Matrix
* Classification Report

---

### 7. اختيار أفضل قيمة K

* استخدام **Elbow Method**
* رسم العلاقة بين K و Error Rate

---

## 📈 النتائج

تم تحسين النموذج باختيار أفضل قيمة لـ K مما أدى إلى تحسين دقة التنبؤ.

---

## 🚀 كيفية التشغيل

1. تأكد من تثبيت المكتبات:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

2. تشغيل الملف:

```bash
jupyter notebook
```

3. افتح ملف:

```
Lab8.ipynb
```

---

## 🧠 ملاحظات

* يجب تطبيق **Scaling** قبل استخدام KNN
* اختيار قيمة K المناسبة يؤثر بشكل كبير على الأداء

---

## 👤 Author

* Your Name
