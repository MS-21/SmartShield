# SmartShield
Predictive maintenance for industrial equipment
## Overview
This project builds a Predictive Maintenance model that forecasts potential equipment failures before they occur. It uses machine learning techniques to analyze historical sensor data and identify patterns associated with machine breakdowns, helping industries reduce downtime and optimize maintenance schedules.
## Problem Statement
Industrial machines often fail due to wear and tear, causing unplanned downtime and costly repairs. 
This project aims to:
- Predict whether a machine will fail in the near future.
- Identify which type of failure is likely to occur.
- Enable proactive maintenance and reduce operational costs.
## Features Used
- Sensor Readings: Air temperature, process temperature
- Operational Data: Rotational speed, torque, tool wear
- Machine Type
- Target Label: Failure mode (multi-class classification)
## Tech Stack
- Languages: Python
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost
- Tools: Jupyter Notebook
## Machine Learning Workflow
- Data Preprocessing
  - Handling missing values
  - Feature scaling and encoding
- Model Training
  - Multiple classifiers were tested: Logistic Regression, SVM, Random Forest, XGBoost
  - Hyperparameter tuning and cross-validation
  - Implemented regularization and pruning techniques to prevent overfitting.
- Evaluation
  - Accuracy, Precision, Recall, F1-score
  - Confusion Matrix and Classification Report
## Results
- Best Model: Random Forest Classifier
- Accuracy Achieved: 98.7%
- Overfitting Prevented: Achieved consistently high performance across training and validation sets, ensuring the model can generalize well to unseen data.
- Excellent performance across all failure categories with strong precision and recall.
