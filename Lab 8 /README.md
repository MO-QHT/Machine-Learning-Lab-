# Lab 8 – K-Nearest Neighbors (KNN)

---

## Overview

This lab focuses on applying the K-Nearest Neighbors (KNN) algorithm to a dataset in order to understand how distance-based classification works. The main goal is to study the importance of feature scaling and determine the best value for K to achieve good model performance.

---

## Data Preparation

### Data Loading
The dataset was imported into a Pandas DataFrame. It contains several numerical features along with a binary target variable labeled as **TARGET CLASS**.

---

## Exploratory Data Analysis (EDA)

Pairplots were used to visualize the relationships between different features and to observe how the two target classes are distributed across the dataset.

---

## Feature Scaling

Standardization was applied using a scaler to normalize feature values. This step is important because KNN relies on distance calculations, and features with larger scales can negatively affect the results if not normalized.

---

## Splitting the Data

The dataset was divided into training and testing sets using a 70% for training and 30% for testing split.

---

## Model Training

An initial KNN model was trained using **K = 1** to create a baseline for comparison.

---

## Model Evaluation

The model performance was evaluated using:
- Confusion Matrix  
- Classification metrics (Precision, Recall, F1-score)  

---

## Selecting the Best K

To find the optimal value of K, multiple values (from 1 to 39) were tested. The error rate was plotted against K, and the elbow method was used to identify the most suitable value.

---

## Final Model

After selecting the best K (around 30), the model was retrained. This resulted in more stable and improved performance compared to the initial baseline.
