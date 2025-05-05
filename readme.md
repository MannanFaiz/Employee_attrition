# Employee Attrition Prediction

This project aims to predict employee attrition (whether an employee will leave the company or not) using machine learning algorithms.

## Project Overview

The goal of this project is to predict employee attrition based on several HR-related features using various machine learning models. The dataset used contains multiple features such as age, job role, salary, and other details. The objective is to predict if an employee will leave the company (Attrition = 1) or stay (Attrition = 0).

## Dataset

The dataset used for this project is sourced from IBM HR Analytics dataset on Kaggle.

- **Dataset**: [IBM HR Analytics: Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **File Name**: `WA_Fn-UseC_-HR-Employee-Attrition.csv`
- **Data Source**: Kaggle
- **Description**: This dataset contains various features like age, gender, job role, education, etc., to predict employee attrition.

### Features:

- **Age**: Age of the employee
- **Attrition**: Whether the employee left (1) or stayed (0)
- **JobRole**: The role of the employee within the company
- **DistanceFromHome**: The distance of the employee’s home from the workplace
- **Education**: Education level of the employee

## Models Used

1. **Logistic Regression**: A linear model used for binary classification.
2. **Decision Tree Classifier**: A model that splits the data into decision nodes.
3. **K-Nearest Neighbors**: A non-parametric method used for classification.
4. **Random Forest Classifier**: A bagging method using multiple decision trees.

## Steps

1. **Data Loading**: Load the dataset and inspect the first few rows.
2. **Data Preprocessing**: Handle missing values, encode categorical variables, and scale numerical features.
3. **Exploratory Data Analysis (EDA)**: Analyze the data to uncover patterns and visualize key trends.
4. **Model Building**: Train multiple models to predict employee attrition.
5. **Model Evaluation**: Evaluate model performance using accuracy score, confusion matrix, and classification report.
6. **Prediction**: Use the models to make predictions on new employee data.

## Requirements

To run this project, you need to install the required libraries.

```bash
pip install -r requirements.txt
