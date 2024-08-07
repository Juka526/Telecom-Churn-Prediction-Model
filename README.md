# Telecom-Churn-Prediction-Model
This repository contains a machine learning model to predict customer churn for a telecommunications company. The model is built using the Decision Tree Classifier from scikit-learn and has been trained on a dataset from Kaggle.

## Dataset

The dataset used in this project is the Telco Customer Churn dataset, which can be found [here](https://bit.ly/telco-csv). The dataset includes customer information such as demographics, account information, and services subscribed to, along with whether the customer has churned.

## Data Preprocessing

1. Loaded the dataset and set `customerID` as the index.
2. Checked the shape and first few rows of the dataset.
3. Checked for missing values and converted the `TotalCharges` column to numeric, replacing empty strings with NaN.
4. Dropped rows with missing values.
5. Identified binary columns and encoded them as numerical variables.

## Exploratory Data Analysis

- Displayed value counts for the target variable `Churn`.
- Plotted the distribution of the target variable `Churn`.

## Feature Selection

- Selected numerical feature columns for the model.
- Split the dataset into features (X) and target (y).

## Data Splitting

- Split the data into training (80%) and testing (20%) sets.

## Model Training

- Initialized the Decision Tree Classifier with specific hyperparameters.
- Trained the model on the training set.

## Model Evaluation

- Predicted on the test set.
- Visualized the decision tree.
- Displayed feature importance.
- Calculated and displayed the accuracy of the model.

## Results

The accuracy of the model on the test set is approximately 73.21%.
