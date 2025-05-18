# Explainable AI (XAI) in Medical Classification

This comprehensive project focuses on the application of Explainable AI (XAI) techniques to address a medical classification problem. The goal is to achieve a balance between predictive performance and interpretability in healthcare applications.

### Project Overview
The project implements and evaluates a diverse set of classification models, integrating multiple XAI techniques to analyze clinical data. This approach aims to improve transparency and provide better decision support in the healthcare field.

### Models Implemented
We compared the performance of nine different classification algorithms:

1. Random Forest
2. XGBoost
3. Multi-layer Perceptron (MLP)
4. Decision Tree
5. CatBoost
6. Support Vector Classifier (SVC)
7. Logistic Regression
8. K-Nearest Neighbors (KNN)
9. Naïve Bayes

### Explainability Techniques
To enhance model transparency and interpretability, we employed the following XAI methods:

- SHAP (SHapley Additive exPlanations)
- LIME (Local Interpretable Model-agnostic Explanations)
- Partial Dependence Plots (PDP)
- Individual Conditional Expectation (ICE) plots

### Key Insights

#### Feature Importance Analysis
We identified the following factors as the most influential predictors:

- ST slope
- Chest pain type
- Cholesterol levels
- Age

#### Interaction Analysis
This analysis was performed using:

- Friedman H-statistic
- Leave-One-Feature-Out (LOFO)

The results revealed non-linear interactions among critical clinical features.

### Clinical Impact
This project establishes a methodology that balances high model accuracy with interpretability, providing practical and explainable insights to support real-world healthcare decision-making.
