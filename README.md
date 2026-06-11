# Customer Churn Prediction using Machine Learning

## Overview

This project focuses on predicting customer churn for a telecom service provider using supervised machine learning techniques. The objective is to identify customers who are likely to discontinue the service, enabling proactive retention strategies.

The project covers the complete machine learning workflow including data preprocessing, exploratory analysis, feature engineering, model training, evaluation, and model persistence.

---

## Problem Statement

Customer churn significantly impacts business growth and profitability. The goal of this project is to develop a predictive model capable of identifying customers at risk of churning based on their demographic information, account details, and service usage patterns.

---

## Dataset

* Dataset: Telco Customer Churn Dataset
* Records: 7,000+ customer entries
* Features:

  * Demographic information
  * Subscription details
  * Contract information
  * Billing and payment attributes
  * Churn status

---

## Project Workflow

### Data Preprocessing

* Missing value treatment
* Data type conversion
* Label encoding and feature transformation
* Removal of irrelevant attributes

### Handling Class Imbalance

* Applied SMOTE (Synthetic Minority Over-sampling Technique) to improve class distribution

### Model Development

Implemented and evaluated multiple machine learning algorithms:

* Decision Tree Classifier
* Random Forest Classifier
* XGBoost Classifier

### Model Evaluation

Performance was assessed using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Cross Validation

### Model Persistence

* Saved trained models using Pickle for future inference and deployment

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Imbalanced-Learn (SMOTE)
* Matplotlib
* Seaborn
* Pickle

---

## Key Outcomes

* Built an end-to-end churn prediction pipeline.
* Improved minority class representation using SMOTE.
* Compared multiple classification algorithms to identify the best-performing model.
* Developed a reusable prediction workflow suitable for deployment scenarios.

---

## Future Improvements

* Hyperparameter Optimization using GridSearchCV
* Stratified K-Fold Cross Validation
* Model Explainability with SHAP
* Deployment using Flask/FastAPI
* Automated ML Pipeline

---

## Author

Arnab Ghosh

Machine Learning | Data Science | Artificial Intelligence
