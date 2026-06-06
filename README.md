# Evaluating Traditional Machine Learning Models for Heart Disease Prediction

## ?? Project Overview

This project evaluates the performance of several traditional machine learning algorithms for predicting heart disease using the UCI Heart Disease dataset. The primary objective is to compare different classification models and investigate the impact of preprocessing and feature selection techniques on predictive accuracy.

The study applies data preprocessing, class balancing, feature selection, and performance evaluation using both Train-Test Split and K-Fold Cross-Validation to identify the most effective model for heart disease prediction.

---

## ?? Features

* Heart disease prediction using supervised machine learning techniques.
* Comparative evaluation of five traditional classification algorithms.
* Data preprocessing and scaling using:

  * Standardization (`StandardScaler`)
  * Min-Max Normalization (`MinMaxScaler`)
* Class balancing through Random Over-Sampling.
* Feature selection using:

  * Pearson Correlation
  * Mutual Information (MI)
  * Recursive Feature Elimination (RFE)
* Model evaluation using Train-Test Split and 9-Fold Cross-Validation.
* Performance comparison based on Accuracy, Precision, Recall, and F1-Score.

---

## ?? Machine Learning Models

The following algorithms were implemented and evaluated:

* Logistic Regression (LR)
* Naïve Bayes (NB)
* Decision Tree (DT)
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)

---

## ?? Dataset
Dataset
Source: https://www.kaggle.com/datasets/thisishusseinali/uci-heart-disease-data
The project uses the **UCI Heart Disease Dataset**, which contains clinical information collected from patients to predict the presence or absence of heart disease.

The dataset includes features such as:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-Induced Angina
* ST Depression
* Slope
* Number of Major Vessels
* Thalassemia
* Target (Heart Disease)

---

## ??? Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## ?? Evaluation Metrics

The models were assessed using:

* Accuracy
* Precision
* Recall
* F1-Score

Cross-validation was also performed to evaluate model robustness and generalization capability.

---

## ?? Results Summary

Experimental results showed that:

* **Decision Tree** achieved the highest overall performance among the evaluated models.
* **Standardization** generally outperformed Min-Max Normalization for most classifiers.
* Feature selection significantly improved prediction performance by reducing irrelevant variables.
* Cross-validation confirmed the stability and reliability of the best-performing models.


