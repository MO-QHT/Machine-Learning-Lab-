# Lab 3: Exploratory Data Analysis (EDA)

---

## Overview

In this lab, Exploratory Data Analysis (EDA) was carried out on the Ames Housing dataset. The main goal was to gain a deeper understanding of the dataset before applying any machine learning models. The analysis focused on studying the structure of the data, identifying missing values, observing distributions, exploring relationships between variables, and detecting possible outliers.

This task represents a regression problem, where the objective is to predict:

**SalePrice** — the selling price of a house.

---

## Dataset

The dataset used in this lab is the Ames Housing dataset from the Kaggle House Prices competition. It includes 79 input features that describe different characteristics of residential properties in Ames, Iowa.

---

## EDA Steps

### 1. Initial Data Exploration
- Imported the dataset using Pandas  
- Checked dataset dimensions (rows and columns)  
- Displayed sample records  
- Reviewed feature names and their data types  
- Generated basic statistical summaries  

### 2. Data Quality Checks
- Looked for missing values in the dataset  
- Checked for duplicate entries  
- Ensured correctness of data types  

### 3. Univariate Analysis
- Studied the distribution of the target variable (SalePrice)  
- Analyzed key numerical features such as GrLivArea  

### 4. Bivariate Analysis
- Explored relationships between SalePrice and:
  - OverallQual  
  - GrLivArea  
  - Neighborhood  
- Used scatter plots and boxplots to visualize patterns  

### 5. Correlation Analysis
- Created a correlation matrix  
- Identified variables strongly related to SalePrice  
- Used heatmaps to better visualize correlations  

### 6. Time-Based Analysis
- Combined YrSold and MoSold to observe trends over time  
- Analyzed how SalePrice changes across different periods  

### 7. Outlier Analysis
- Investigated extreme values in features like living area and price  
- Detected possible outliers using visual methods  

---

## Conclusion

The EDA process helped in understanding the dataset more clearly, including its structure, important variables, and potential data issues. These findings are essential for improving data preprocessing and building more accurate machine learning models in later stages.

