# Intelligent Hospital Triage Decision Support System

## Project Overview

This project presents a hybrid hospital triage decision-support system designed to assist emergency departments in prioritizing patients using emergency room operational data.

The system combines rule-based severity assignment with machine learning techniques to analyze patient information and evaluate triage consistency.

---

## Problem Statement

Emergency departments often experience high patient volumes, making effective prioritization critical.

The dataset used in this study did not contain explicit triage labels. Therefore, clinically inspired severity categories were engineered using operational indicators such as admission status and patient wait times.

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Joblib

---

## Machine Learning Models

* Decision Tree Classifier
* Random Forest Classifier
* Logistic Regression

---

## Workflow

1. Data Cleaning
2. Missing Value Handling
3. Feature Engineering
4. Rule-Based Severity Assignment
5. Feature Encoding
6. Model Training
7. Model Evaluation
8. Confusion Matrix Analysis
9. Feature Importance Analysis
10. Model Export

---

## Key Findings

* Initial experiments demonstrated label leakage due to the use of severity-generating variables during training.
* Feature redesign led to more realistic model performance.
* Random Forest performed best among the evaluated algorithms.
* Logistic Regression struggled because of class imbalance and the absence of strong linear relationships.

---

## Repository Structure

notebooks/ – Colab notebook

dataset/ – Emergency room dataset

models/ – Saved machine learning models

screenshots/ – Visualizations

---

## Future Improvements

* Incorporate clinically validated triage labels.
* Apply SMOTE for class balancing.
* Develop a Flask-based web interface.
* Integrate explainable AI techniques such as SHAP.

---

## Author

Aditi Bhalerao
