# Machine Learning Lab – Dataset Exploration & Methodology

This lab applies the fundamental steps of a machine learning workflow, starting from dataset selection and ending with the design of a complete methodology diagram.

---

## Part 1: Choosing an Open Dataset

An open dataset titled **Screen Time, Sleep & Stress Analysis** was selected for this lab.

The dataset contains 50,000 structured user records analyzing:
- Smartphone usage behavior  
- Sleep patterns  
- Stress levels  
- Workplace productivity indicators  

The dataset is clean, structured, and formatted for machine learning analysis.

**Dataset Source:**  
https://www.kaggle.com/datasets/amar5693/screen-time-sleep-and-stress-analysis-dataset

---

## Part 2: Defining the Machine Learning Problem

This project addresses a machine learning problem using the Screen Time, Sleep & Stress dataset. The dataset provides structured behavioral and demographic information related to smartphone usage, sleep duration, stress levels, and workplace productivity indicators.

The primary objective of this project is to analyze how lifestyle and smartphone usage patterns influence an individual’s stress level. By examining relationships between features such as daily screen time, sleep duration, device type, occupation, and age, the model aims to identify patterns that contribute to increased or decreased stress levels.


### Problem Type:
Regression

### Target Variable:
Stress Level

### Model Objective:
The goal is to analyze smartphone usage, sleep behavior, and demographic features to predict an individual's stress level.

The model will learn patterns from behavioral and usage features and estimate stress scores for unseen data.

---

## Part 3: Loading and Inspecting the Dataset in Python

The dataset was uploaded to the repository and loaded using Python and the Pandas library.

[Open Notebook](LLab2 Part3.ipynb)
