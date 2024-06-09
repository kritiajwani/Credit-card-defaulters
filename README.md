# Loan Category and Dishonour of Bill Analysis

This repository contains a Google Colab notebook that analyzes the impact of loan categories on the dishonour of bills using XGBoost.

## Project Overview

The purpose of this project is to demonstrate how different loan categories affect the number of dishonoured bills. This analysis is performed using XGBoost, a powerful machine learning algorithm, and various data visualization techniques.

## Dataset

The dataset contains the following columns:

- `Customer_ID`
- `Age`
- `Gender`
- `Occupation`
- `Marital Status`
- `Family Size`
- `Income`
- `Expenditure`
- `Use Frequency`
- `Loan Category`
- `Loan Amount`
- `Overdue`
- `Debt Record`
- `Returned Cheque`
- `Dishonour of Bill`

## Notebooks

- `Loan_Category_Dishonour_Analysis.ipynb`: This notebook contains the code to:
  - Preprocess the data
  - Encode categorical variables
  - Train an XGBoost model to predict the number of dishonoured bills based on the loan category
  - Evaluate the model performance
  - Visualize the feature importances and the impact of loan categories on the number of dishonoured bills

## Installation and Usage
