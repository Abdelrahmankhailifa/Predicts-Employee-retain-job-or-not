# Human Resources Employee Turnover Analysis

This repository contains Python code for analyzing employee turnover in a Human Resources dataset. The dataset, stored in a CSV file, includes various attributes such as satisfaction level, average monthly hours, promotion status, and salary.

## Key Steps

### 1. Data Loading and Exploration
- The data is loaded using pandas, and initial exploration includes displaying the first few rows of the dataset.

### 2. Data Preprocessing
- The dataset is split into two subsets: employees who left the company (`left == 1`) and those who were retained (`left == 0`).
- A subset of relevant columns is selected for analysis (`satisfaction_level`, `average_monthly_hours`, `promotion_last_5years`, `salary`).
- Categorical variables, such as salary, are one-hot encoded to prepare the data for machine learning.

### 3. Machine Learning
- The dataset is split into training and testing sets using scikit-learn's `train_test_split`.
- A logistic regression model is created and trained using the training data.
- The model's accuracy is evaluated on the testing set.

## How to Use
1. Download the HR dataset (`HR_comma_sep.csv`) and update the file path in the code.
2. Run the provided Python script or Jupyter Notebook to perform data analysis and machine learning tasks.
3. Explore and modify the code to suit your specific HR analytics needs.

## Dependencies
- pandas
- matplotlib
- scikit-learn

Feel free to contribute, suggest improvements, or adapt the code for your own datasets.
