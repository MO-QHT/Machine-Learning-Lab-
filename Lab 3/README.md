# Lab 3 – Exploratory Data Analysis (EDA)

## Overview

In this lab, I applied Exploratory Data Analysis (EDA) techniques to understand the dataset before building any machine learning models. EDA is a critical step in the ML workflow because it allows us to explore data structure, detect issues, identify patterns, and understand relationships between variables.

---

## EDA Process

### 1. Data Inspection

- Loaded the dataset using Pandas
- Examined dataset shape (rows and columns)
- Reviewed column names and data types
- Generated summary statistics


### 2. Data Cleaning Checks

- Identified missing values
- Checked for duplicate rows
- Verified data types


### 3. Univariate Analysis

- Analyzed the distribution of the target variable (SalePrice)
- Examined distributions of important numerical features such as GrLivArea


### 4. Bivariate Analysis

- Explored relationships between SalePrice and:
  - OverallQual
  - GrLivArea
  - Neighborhood
- Visualized patterns using scatter plots and boxplots


### 5. Correlation Analysis

- Computed correlation matrix
- Identified features strongly correlated with SalePrice
- Visualized correlations using a heatmap


### 6. Time-Based Analysis

- Combined YrSold and MoSold to analyze monthly sale trends
- Examined how average SalePrice changes over time


### 7. Outlier Detection

- Investigated extreme values in living area and sale price
- Identified potential outliers visually

---
## Conclusion

This lab helped me understand how to explore and interpret structured business data before applying machine learning models. Performing EDA ensures better feature selection, improved model performance, and stronger data-driven decision-making.

EDA is a foundational step in the machine learning lifecycle, and this lab strengthened my ability to analyze real-world datasets effectively.

