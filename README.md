# XAI-Project
A comprehensive project focusing on Explainable AI (XAI) techniques applied to a medical classification problem, aiming to balance predictive performance and interpretability in healthcare applications.

 Project Overview:
This project implements and evaluates a diverse set of classification models and integrates multiple XAI techniques to analyze clinical data for improved transparency and decision support.

 Models Implemented:
We compared the performance of 9 different classification algorithms:

Random Forest

XGBoost

Multi-layer Perceptron (MLP)

Decision Tree

CatBoost

Support Vector Classifier (SVC)

Logistic Regression

K-Nearest Neighbors (KNN)

Naïve Bayes

Explainability Techniques:
To enhance model transparency and interpretability, the following XAI methods were employed:

SHAP (SHapley Additive exPlanations)

LIME (Local Interpretable Model-agnostic Explanations)

Partial Dependence Plots (PDP)

Individual Conditional Expectation (ICE) plots

Key Insights:
Feature Importance Analysis highlighted:

ST-slope

Chest pain type

Cholesterol

Age
as the most influential predictors.

Interaction Analysis was performed using:

Friedman H-statistic

Leave-One-Feature-Out (LOFO)
to reveal non-linear interactions among clinical features.

Clinical Impact:

The project proposes a methodology that balances high model accuracy with interpretability, offering practical insights for real-world healthcare decision-making.
