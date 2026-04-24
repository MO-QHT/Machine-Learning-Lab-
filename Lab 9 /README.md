# Lab 9 – Decision Trees and Random Forest

---

## Overview

This lab focuses on building and comparing two classification models: Decision Tree and Random Forest, using loan data from LendingClub. The objective is to predict whether a borrower will fully repay a loan based on financial and credit-related features.

---

## Data Preparation

### Data Loading
The dataset was loaded into a Pandas DataFrame. It contains information such as credit score, income level, debt ratio, and loan purpose. The target variable used for prediction is **not.fully.paid**.

---

## Exploratory Data Analysis (EDA)

Several visualizations were used to better understand the dataset:
- Histograms to compare FICO score distributions across groups  
- Count plots to examine loan purposes in relation to repayment status  
- Jointplots to study relationships between FICO score and interest rate  

---

## Feature Engineering

- The categorical variable **purpose** was transformed into numerical form using dummy variables  
- This conversion allows machine learning models to process categorical data effectively  

---

## Train-Test Split

The dataset was divided into training and testing sets using a 70/30 split to evaluate model performance.

---

## Decision Tree Model

- A Decision Tree classifier was trained on the dataset  
- Performance was evaluated using a confusion matrix and classification report  
- The model showed reasonable results but indicated signs of overfitting and issues related to class imbalance  

---

## Random Forest Model

- A Random Forest model (with around 600 trees) was trained  
- Predictions were evaluated using the same metrics as the Decision Tree  
- The model produced more stable and improved results  

---

## Model Comparison

- Random Forest performed better overall compared to the Decision Tree  
- It handled overfitting more effectively due to averaging multiple trees  
- However, class imbalance still affected recall for the minority class  

---

## Key Takeaways

- Decision Trees are easy to understand but can overfit the data  
- Random Forest improves performance by combining multiple trees  
- Proper handling of categorical features is important  
- Imbalanced datasets can negatively affect model evaluation results  
