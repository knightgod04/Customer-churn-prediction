# Customer Churn Prediction Using Machine Learning

## Overview

Customer churn is a major challenge for subscription-based businesses. This project analyzes customer behaviour, identifies factors associated with churn, and develops a machine learning model to predict customers who are likely to leave.

The project combines statistical analysis and machine learning techniques to generate both predictive results and business insights.

---

## Objectives

- Analyze customer characteristics influencing churn
- Identify statistically significant factors affecting customer retention
- Build a classification model for churn prediction
- Evaluate model performance using appropriate metrics

---

## Dataset

Dataset:
Telco Customer Churn Dataset

Source:
Kaggle

The dataset contains 7,043 customer records with information related to:

- Customer demographics
- Services subscribed
- Contract details
- Billing information
- Churn status

---

## Methodology

### 1. Data Preprocessing

- Missing value handling
- Removal of irrelevant features
- Categorical variable encoding
- Feature scaling

### 2. Exploratory Data Analysis

Performed analysis using:

- Distribution plots
- Box plots
- Correlation heatmaps

### 3. Statistical Analysis

Applied:

- Chi-square test of independence
- Welch's t-test

### 4. Machine Learning

Model used:

- Logistic Regression

Evaluation metrics:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC Score

---

## Key Findings

- Contract type has a significant relationship with churn.
- Customers with shorter tenure show higher churn tendencies.
- Monthly charges differ significantly between churned and retained customers.

---

## Model Performance

| Metric | Score |
|---|---|
| Accuracy | 78.96% |
| Precision | 63% |
| Recall | 50% |
| F1-score | 56% |
| ROC-AUC | 0.828 |

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statistical Hypothesis Testing

---

## Project Structure
Customer-Churn-Prediction/
│
├── Customer_Churn_Analysis.ipynb
├── Customer_Churn_Report.pdf
├── Telco-Customer-Churn.csv


---

## Future Improvements

- Handle class imbalance techniques
- Compare multiple machine learning algorithms
- Hyperparameter tuning
- Deployment using Streamlit
