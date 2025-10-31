Name: Swara Sunil Patil
Roll No: MM22B045
Model Selection — Satellite Dataset

This project focuses on model selection and evaluation for the Satellite dataset.
The goal is to compare different machine learning algorithms and identify the best model for multiclass classification.

Models implemented include KNN, SVC, Logistic Regression, Decision Tree, Naive Bayes, Dummy Classifier, Random Forest, XGBoost, and a Random Model used as a baseline.

The workflow involved loading and preprocessing the data (including feature standardization and removal of class 7), training each model separately, and evaluating them using Accuracy, Weighted F1-score, ROC-AUC, and Precision–Recall Average Precision (PRC-AP).
Both macro and micro-averaged ROC and PRC curves were analyzed to assess model stability and generalization.

SVC and KNN showed the best overall performance across most metrics.
Random Forest and XGBoost also performed well, providing consistent results through ensemble learning.
The Random Model served as a performance baseline and behaved as expected, showing near-random results.
Overall, SVC was identified as the most balanced and reliable model for this dataset.
