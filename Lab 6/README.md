# ARTI 308 – Lab 6: Regression Modeling on E-commerce Customer Data

---

## Overview

This lab focuses on applying regression techniques to an e-commerce customer dataset. The main objective is to build a machine learning model that can estimate how much a customer spends annually based on their behavior.

Key features used in the analysis include:
- Average Session Length  
- Time Spent on App  
- Time Spent on Website  
- Length of Membership  

Since the dataset is already clean and does not contain missing values or inconsistencies, the lab mainly emphasizes data exploration, selecting relevant features, and building a regression model.

---

## Objectives

The following steps were carried out in this lab:

- Import the dataset into a DataFrame  
- Explore the dataset using basic inspection methods such as head(), info(), and describe()  
- Perform simple data cleaning where necessary  
- Remove columns that are not useful for prediction (e.g., Email, Address, Avatar)  
- Define the target variable (Yearly Amount Spent)  
- Select the most relevant features for the model  
- Split the data into training and testing sets  
- Train a Linear Regression model  
- Evaluate the model using regression performance metrics  

---

## Student Tasks

**Task 1:**  
Load the dataset and examine its structure using basic exploration functions.

**Task 2:**  
Clean the dataset and explain the reason for removing irrelevant columns.

**Task 3:**  
Prepare the data for modeling by defining input features (X) and target variable (y), then split the dataset.

**Task 4:**  
Train a Linear Regression model and evaluate its performance using MAE, MSE, RMSE, and R².

---

## Summary

This lab demonstrates how regression models can be used to predict customer spending behavior. The results show strong performance, with a high R² value indicating that the selected features explain a large portion of the variation in yearly spending. In particular, factors such as membership duration and time spent on the app play an important role in predicting customer expenditure.
