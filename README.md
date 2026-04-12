# 📊 Data Science Internship Projects – CodSoft

## 📌 Overview

This repository contains all the projects completed during my Data Science Internship at CodSoft. The internship focused on applying machine learning techniques to real-world datasets, covering classification, prediction, and handling imbalanced data.

Each task demonstrates a complete machine learning workflow including data preprocessing, model building, evaluation, and result interpretation.

---

## 📂 Projects Included

### 🔹 1. Titanic Survival Prediction

* **Problem Type:** Binary Classification
* **Goal:** Predict whether a passenger survived the Titanic disaster

**Key Steps:**

* Data cleaning and handling missing values
* Feature engineering (e.g., family size)
* Encoding categorical variables
* Model training using multiple algorithms

**Models Used:**

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Decision Tree
* Random Forest

---

### 🔹 2. Iris Flower Classification

* **Problem Type:** Multi-class Classification
* **Goal:** Classify iris flowers into Setosa, Versicolor, and Virginica

**Key Steps:**

* Exploratory Data Analysis (EDA)
* Data preprocessing and scaling
* Model comparison

**Models Used:**

* Logistic Regression
* KNN
* SVM
* Decision Tree
* Random Forest

**Result:**

* All models achieved 100% accuracy due to the well-structured and separable nature of the dataset

---

### 🔹 3. Credit Card Fraud Detection ⭐

* **Problem Type:** Binary Classification (Imbalanced Dataset)
* **Goal:** Detect fraudulent transactions

**Key Challenges:**

* Highly imbalanced dataset (0.172% fraud cases)
* Accuracy not reliable

**Key Steps:**

* Data preprocessing and feature selection
* Train-test split with stratification
* Model training before and after handling imbalance
* Applying SMOTE (Synthetic Minority Over-sampling Technique)

**Models Used:**

* Logistic Regression
* KNN
* Decision Tree
* Random Forest
* SVM

---

## 📊 Results & Insights

### 🔹 Key Observations:

* High accuracy does not guarantee good performance in imbalanced datasets
* Recall is the most important metric in fraud detection
* SMOTE significantly improves the model’s ability to detect fraud cases
* There is a trade-off between precision and recall

### 🔹 Best Model:

* **Random Forest (after SMOTE)**
* Achieved the best balance between precision and recall

---

## 📈 Visualizations

The projects include:

* Class distribution before and after SMOTE
* Model comparison graphs (Recall & Precision)
* Confusion matrices

These visualizations help in understanding model performance and the impact of data balancing techniques.

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🧠 Key Learnings

* Building end-to-end machine learning pipelines
* Handling missing data and feature engineering
* Understanding and solving class imbalance problems
* Evaluating models using appropriate metrics
* Comparing multiple algorithms effectively

---

## 🚀 Conclusion

This internship provided hands-on experience in solving real-world machine learning problems. It highlighted the importance of data preprocessing, proper evaluation techniques, and model comparison.

The Credit Card Fraud Detection project, in particular, demonstrated how handling class imbalance can significantly improve model performance and make predictions more reliable in practical scenarios.

---

### 📁 Dataset

Titanic dataset from Kaggle
