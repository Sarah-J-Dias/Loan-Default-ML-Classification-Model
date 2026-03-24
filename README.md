# Loan-Default-ML-Classification-Model

I created this ML classification model as part of a team project with the National Student Data Corps (NSDC) organization at UCLA. The goal of this project was to build a ML classification model to predict whether an SBA (Small Business Administration) loan would be paid in full or charged off (defaulted), using features like industry, number of employees, and jobs created. 
The full dataset can be found on Kaggle here: https://lnkd.in/gQJJ2DUe

This repository contains our ML pipeline broken down into 4 parts:
1. Data Preprocessing (1_Data_Preprocessing.ipynb)
   * Loading and inspecting the raw SBA dataset
   * Handling missing values and duplicates
   * Dropping data leakage columns
   * Cleaning monetary columns
   * Encoding categorical variables
   * Exporting a cleaned CSV
2. Exploratory Data Analysis (2_EDA.ipynb)
   * Summary statistics and correlation analysis
   * Distribution plots
   * Visualizations of loan default rates by industry, state, franchise status, approval year, and bank.
3. Creating Classification Models (3_Classification_Models.ipynb)
   * Training and tuning 5 classification models (Logistic Regression, Decision Trees, Random Forest, KNN, and XGBoost) using cross-validation and RandomizedSearchCV
   * SHAP feature importance analysis.
5. Model Comparison and Final Model Insights (4_Model_Comparison_and_Insights.ipynb)
   * Comparing models using ROC-AUC, Precision-Recall, and calibration curves
   * Gini coefficient (0.95), Brier score, lift charts, and a business value estimation.
  

For more information on NSDC, please visit: 
https://www.nsdcucla.com/ and https://www.linkedin.com/company/nsdcucla/


