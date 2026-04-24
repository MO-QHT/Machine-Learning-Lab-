# ARTI 308 – Lab 5: Feature Engineering for Order Status Prediction

---

## Overview

This lab focuses on applying feature engineering techniques to a classification problem using a food delivery dataset. The goal is to build a baseline model that can predict the status of an order.

The possible outcomes include:
- Delivered  
- Cancelled  
- In Transit  

Since the dataset is already clean (no missing values, duplicates, or data inconsistencies), the main focus of this lab is on creating useful new features and analyzing how they affect model performance.

---

## Objectives

The work in this lab follows these main steps:

- Load and explore the dataset  
- Define the target variable (Order_Status)  
- Choose relevant features while avoiding data leakage  
- Create new engineered features such as:
  - Time-related features  
  - Price-related features  
  - Distance-related features  
- Handle categorical variables with high cardinality  
- Apply encoding techniques for categorical data  
- Train a baseline model using Random Forest  
- Evaluate model performance  
- Study feature importance  

---

## Summary

This lab highlights the importance of feature engineering in improving machine learning models. By introducing new features related to time, price, and distance, and simplifying categorical variables, the model becomes more capable of identifying patterns in the data. Additionally, analyzing feature importance helps in understanding which variables contribute most to predicting the order status.
