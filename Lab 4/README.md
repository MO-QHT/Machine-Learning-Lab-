# Lab 4: Data Quality Assessment and Preprocessing

---

## Overview

In this lab, several data preprocessing techniques were applied to the Ames Housing dataset in order to enhance data quality and prepare it for machine learning models. The work included identifying common data issues, handling missing values, detecting and treating outliers, scaling numerical features, and applying Principal Component Analysis (PCA) for dimensionality reduction.

This dataset is used for a regression task, where the goal is to predict:

**SalePrice** — the final selling price of a house.

---

## Dataset

The dataset used is the Ames Housing dataset from the Kaggle House Prices competition.

---

## Work Performed

### 1. Data Quality Assessment
- Searched for missing values in the dataset  
- Checked for duplicate records  
- Reviewed and validated data types  
- Identified numerical and categorical features  

### 2. Handling Missing Data
- Filled missing values in numerical features using the median  
- The median was selected because it is less affected by extreme values and works well with skewed data  

### 3. Outlier Detection and Treatment (IQR Method)
- Applied the Interquartile Range (IQR) technique  
- Determined lower and upper boundaries for acceptable values  
- Removed data points that fall outside these limits  

### 4. Feature Scaling
Two normalization techniques were applied:

- **Min-Max Scaling**
  - Transforms values to a range between 0 and 1  

- **Z-Score Standardization**
  - Centers data around mean = 0  
  - Scales data to standard deviation = 1  

### 5. Dimensionality Reduction (PCA)
- Applied PCA on the normalized numerical features  
- Plotted cumulative explained variance  
- Determined the number of components needed to retain most of the information  

---

## Conclusion

This lab covered important preprocessing steps required before building machine learning models. The dataset was cleaned, scaled, and reduced in dimensionality using PCA, making it more suitable for further analysis and modeling.

