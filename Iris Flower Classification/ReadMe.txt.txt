# 🌸 Iris Flower Classification

## 📌 Project Overview

This project focuses on classifying iris flowers into three different species — *Setosa*, *Versicolor*, and *Virginica* — using machine learning algorithms. The classification is based on four features: sepal length, sepal width, petal length, and petal width.

The goal of this project is to understand and implement a complete machine learning workflow, including data preprocessing, model training, evaluation, and comparison.

---

## 📂 Dataset

The dataset used in this project is the famous Iris dataset, which is available in the sklearn library.

It contains:

* 150 samples
* 3 classes of iris flowers
* 4 numerical features:

  * Sepal Length
  * Sepal Width
  * Petal Length
  * Petal Width

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔄 Workflow

1. **Data Loading**

   * Loaded dataset using sklearn datasets

2. **Exploratory Data Analysis (EDA)**

   * Pairplot visualization
   * Correlation heatmap
   * Checked for missing values

3. **Data Preprocessing**

   * Feature and target separation
   * Train-test split (80-20)
   * Feature scaling using StandardScaler

4. **Model Training**
   The following machine learning models were applied:

   * Logistic Regression
   * K-Nearest Neighbors (KNN)
   * Support Vector Machine (SVM)
   * Decision Tree
   * Random Forest

5. **Model Evaluation**

   * Accuracy Score
   * Classification Report
   * Confusion Matrix

---

## 📊 Results

All models achieved **100% accuracy** on the test dataset.

This is because the Iris dataset is clean, well-structured, and the classes are highly separable, making it easier for machine learning models to perform accurate classification.

---

## 🏁 Conclusion

In this project, multiple machine learning algorithms were successfully applied to classify iris flower species. All models performed equally well with perfect accuracy, highlighting the simplicity and separability of the dataset.

Since performance metrics were identical, model selection can be based on factors such as simplicity, interpretability, and computational efficiency. Logistic Regression offers a simple and fast solution, while Random Forest provides robustness for more complex scenarios.

This project demonstrates the importance of data preprocessing, model comparison, and proper evaluation in building effective machine learning models.

---

## 📚 Key Learnings

* Understanding classification problems
* Importance of data preprocessing and scaling
* Applying multiple machine learning algorithms
* Evaluating models using different metrics
* Comparing model performance effectively

---

## 🚀 Future Improvements

* Hyperparameter tuning for models
* Visualizing decision boundaries
* Building a simple web app using Streamlit
* Applying the workflow to more complex datasets

---

