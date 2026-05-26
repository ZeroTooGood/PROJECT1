
# Heart Disease Prediction and Patient Segmentation using Machine Learning

## Dataset Source

Kaggle Dataset:
https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

---

# 1. Introduction

Heart disease is one of the leading causes of death worldwide. Machine learning can help healthcare organizations identify patients at risk and improve diagnosis accuracy.

This project applies both supervised and unsupervised machine learning techniques on the Heart Disease dataset.

Techniques used:
- Simple Linear Regression
- Multiple Linear Regression
- Logistic Regression
- K-Means Clustering
- Hierarchical Clustering

---

# 2. Problem Statement

Objectives of the project:

1. Predict cholesterol levels using regression techniques
2. Predict heart disease using Logistic Regression
3. Segment patients using clustering algorithms
4. Compare machine learning model performance

---

# 3. Dataset Description

The dataset contains medical attributes such as:

| Feature | Description |
|---|---|
| age | Patient age |
| chol | Cholesterol level |
| trestbps | Resting blood pressure |
| thalach | Maximum heart rate |
| oldpeak | ST depression |
| target | Heart disease presence |

---

# 4. Data Preprocessing

Steps performed:

- Duplicate removal
- Missing value checking
- Feature scaling
- Feature selection

---

# 5. Exploratory Data Analysis

EDA techniques used:

- Count plots
- Histograms
- Correlation heatmap

Key observations:

- Cholesterol increases with age
- Blood pressure impacts heart disease risk
- Some features show strong correlation with target variable

---

# 6. Simple Linear Regression

## Objective

Predict cholesterol using age.

## Evaluation Metrics

- R² Score
- RMSE
- MAE

---

# 7. Multiple Linear Regression

## Objective

Predict cholesterol using:
- age
- trestbps
- thalach
- oldpeak

Additional techniques:
- VIF
- RFE

MLR performs better than SLR because multiple health indicators are used.

---

# 8. Logistic Regression

## Objective

Predict heart disease.

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC Curve
- AUC

The model successfully classifies patients into disease and non-disease groups.

---

# 9. K-Means Clustering

## Objective

Group patients into clusters.

## Features Used

- age
- chol
- trestbps
- thalach

Techniques:
- Elbow Method
- Silhouette Score

Cluster interpretation:
- Cluster 0: Younger healthy patients
- Cluster 1: Medium-risk patients
- Cluster 2: High-risk patients

---

# 10. Hierarchical Clustering

Hierarchical clustering visualizes relationships between patient groups using dendrograms.

---

# 11. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

---

# 12. Conclusion

This project demonstrated how machine learning techniques can assist in healthcare analytics and disease prediction.

Both supervised and unsupervised learning methods provided meaningful insights into patient health conditions.
