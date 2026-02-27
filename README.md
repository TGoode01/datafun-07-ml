# DataFun 07 – Machine Learning Project

## Project Overview

This project explores foundational machine learning concepts using Python and Scikit-learn.  
It walks through the complete ML workflow: data exploration, preprocessing, model training, evaluation, and interpretation.

The purpose of this project is to strengthen practical machine learning skills and demonstrate the ability to:

- Perform exploratory data analysis (EDA)
- Prepare data for modeling
- Train and evaluate classification models
- Interpret model performance metrics

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code
- Git & GitHub

---

## Project Workflow

1. Data Loading 
2. Data Cleaning  
3. Exploratory Data Analysis  
4. Model Training  
5. Model Evaluation  
6. Conclusions & Insights  



### Clone the repository

```bash
git clone https://github.com/TGoode01/datafun-07-ml
cd datafun-07-ml

---

## Create a Virtual Environment

Creating a virtual environment ensures that project dependencies remain isolated.

```bash
python -m venv .venv

.venv\Scripts\activate
source .venv/bin/activate



### Part 2 - Prediction (SciPy)
- Dataset: Historical average high temperatures in NYC for January (1895–2018)
- Method: Linear Regression using SciPy
- Goal: Predict the average high temperature in January 2024
- Key Steps:
  1. Load CSV into DataFrame (`nyc_df`)
  2. Inspect and clean data (Year column, missing values)
  3. Compute descriptive statistics
  4. Build linear regression model (`slope`, `intercept`)
  5. Predict value for 2024
  6. Visualize scatter plot with best-fit line

**Predicted Avg High Temp for Jan 2024:** 38.59°F