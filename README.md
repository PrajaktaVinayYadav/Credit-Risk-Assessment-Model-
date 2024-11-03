# Credit Risk Assessment Model for Predicting Loan Defaults using XGBoost
# Project Overview
This project focuses on developing a Credit Risk Assessment Model to predict loan defaults. Using XGBoost as the primary algorithm, the project addresses the challenge of imbalanced financial data, aiming to accurately identify high-risk borrowers while maintaining overall model performance.

# Key Steps and Techniques
# 1. Data Preprocessing
Data Cleaning: Handled missing values and inconsistent data entries to improve data quality.
Feature Engineering: Performed transformations, scaling, and encoding to optimize features for the XGBoost model.
Train-Test Splitting: Divided data into training and testing sets to evaluate model performance on unseen data.

# 2. Imbalanced Data Handling
SMOTE (Synthetic Minority Oversampling Technique): Applied SMOTE to balance the classes by oversampling the minority class (defaults). Different sampling ratios were tested to improve recall and precision for identifying loan defaults.

# 3.Model Development and Optimization
Algorithm Selection: Used XGBoost for its performance with tabular data and ability to handle imbalanced classes with adjustments.
Hyperparameter Tuning: Conducted grid search on hyperparameters such as learning_rate, max_depth, subsample, and scale_pos_weight to enhance model accuracy and recall.
Performance Metrics: Focused on F1 Score, Precision, and Recall to evaluate the model’s success in predicting loan defaults without significantly impacting accuracy.

# 4. Results
I achieved an accuracy of 0.78 and a cross-validated F1 Score of 0.686 for the tuned XGBoost model. This balance of metrics demonstrates the model's effectiveness in identifying high-risk loans with acceptable overall accuracy.

# Skills and Tools
Algorithm: XGBoost
Data Handling: SMOTE for class imbalance
Model Evaluation: Precision, Recall, F1 Score
Hyperparameter Tuning: GridSearchCV
Tools and Libraries: Python, Scikit-Learn, XGBoost, Imbalanced-Learn
