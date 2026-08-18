# Customer Churn Prediction

## Overview

A machine learning project that predicts whether a customer is likely to churn. The project focuses on data analysis, preprocessing, classification, model evaluation, and identifying the factors that influence customer churn.

## Dataset

The dataset contains customer information such as:

tenure months
monthly usage hours	
has multiple devices	
customer support calls	
payment failures	
is premium plan	
churn

The target variable is **Churn**.

## Approach

The project follows a complete machine learning workflow:

1. Exploratory Data Analysis (EDA)
2. Data preprocessing and feature encoding
3. Feature engineering
4. Train/test split
5. Model training and comparison
6. Evaluation using multiple classification metrics
7. Confusion matrix analysis
8. Feature importance analysis
9. SHAP explainability
10. Saving the final model with `joblib`

## Models

Several classification models were evaluated, including:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

The models were compared using:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC

Because missing potential churners can be costly for a business, **Recall and ROC-AUC** were given particular attention.

## Key Results

The final model was selected based on overall predictive performance and its ability to identify customers at risk of churn.

Feature importance and SHAP analysis were used to understand which customer characteristics had the greatest influence on predictions.

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn
* SHAP
* Joblib
* Jupyter Notebook

## Project Structure

```text
customer-churn-prediction/
├── data/
├── notebooks/
├── models/
├── src/
├── requirements.txt
└── README.md
```

## Purpose

This project demonstrates an end-to-end Data Science workflow, from exploratory analysis and preprocessing to model development, evaluation, and model explainability.
