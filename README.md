Coronavirus Recovery Prediction Project

Overview
This project uses machine learning classifiers to predict whether a person will recover from coronavirus symptoms. The prediction is based on standard symptoms provided by the World Health Organization (WHO) and a preprocessed dataset of daily time series data.

Dataset
The dataset (data.csv) contains cumulative daily information on:

Number of cases: Affected, deaths, recoveries.
Time frame: Data available from January 22, 2020.
Key Features:
Country: Country of residence.
Location: Specific location within the country.
Age: WHO-defined age groups.
Gender: Male or Female.
Visited_Wuhan: Whether the person visited Wuhan, China.
From_Wuhan: Whether the person is from Wuhan, China.
Symptoms: Represented in six coded fields.
Time_before_symptoms_appear: Time elapsed before symptom onset.
Result: Outcome - death (1) or recovered (0).
Objective
The goal is to design and evaluate multiple classifiers to predict patient outcomes using the dataset features.

Methodology
Data Partitioning:
Training set for model training.
Validation set for hyperparameter tuning.
Testing set for final evaluation.
Classifiers:
K-Nearest Neighbors (KNN)
Logistic Regression
Naïve Bayes (due end of week 11)
Decision Trees
Support Vector Machines (SVM) (due end of week 14)
Evaluation Metrics
Each classifier will be assessed using the following metrics:

Precision
Recall
F1-Score
ROC/AUC Curves
