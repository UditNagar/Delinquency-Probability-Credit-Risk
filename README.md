# Delinquency Probability of a Customer
Based on Kaggle Competition: Give Me Some Credit

The Data Dictionary, Training and Test Sets belongs to Kaggle and Competition creator.

This notebook is created 9 years after this competition ended. The main aim of this project is to predict the probabily whether a customer will default in the future given his record present in the dataset. We will be using predict_proba to determine the delinquency probabilities of the customer.

The Highlights of the notebook are:

Exploratory Data Analysis
  (**Outlier Analysis**,
  **Null Handling**,
  **Distribution Analysis**,
  **Skewness Reduction (using Box Cox Transformation)**),
Feature Engineering,
LightGBM using RandomizedSearchCV (Classification) and XGBoost using RandomizedSearchCV (Classification).


  The Evaluation Metrics used are:
  **Mean Squared Error,
  Root Mean Squared Error,
  Mean Absolute Error,
  Mean Squared Logarithmic Error,
  Root Mean Square Logarithmic Error,
  Accuracy on Training Set,
  Accuracy on Test Set,
  F-Beta Score (Beta = 2),
  F1 Score,
  Precision,
  Recall,
  Confusion Matrix
  and AUC Curve**.
The Probability Prediction and Delinquency Prediction on Validation Sets. The Feature Importances are also visualized for
  **Summary Plot and
  SHAP Analysis**
