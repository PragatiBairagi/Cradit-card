# Cradit-card
Credit Card Fraud Detection
This repository contains a Jupyter Notebook for detecting credit card fraud using machine learning techniques. The notebook includes data preprocessing, model training, evaluation, and visualization.

Project Overview
The goal of this project is to build a machine learning model that can accurately detect fraudulent credit card transactions. The dataset used for this project is the 'creditcard.csv' dataset, which contains transaction details and labels indicating whether a transaction is fraudulent or not.

Dataset
Source: The dataset is publicly available on Kaggle.
Features: The dataset includes various features representing transaction details.
Target: The target variable indicates whether a transaction is fraudulent (1) or not (0).
Notebook Contents
Data Exploration:

Load and preview the dataset
Check for missing values
Statistical summary of features
Data Preprocessing:

Feature scaling
Handling imbalanced data using techniques like SMOTE
Model Training:

Split data into training and testing sets
Train models such as Logistic Regression, Decision Tree, Random Forest, and others
Hyperparameter tuning using GridSearchCV
Model Evaluation:

Evaluate models using metrics like accuracy, precision, recall, F1-score, and AUC-ROC
Compare performance of different models
Visualization:

Plot confusion matrices
Visualize feature importance
Dependencies
Python 3.x
NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn

Results
The final model achieved an accuracy of 99.67% on the test set.
Detailed performance metrics and visualizations are provided in the notebook.
