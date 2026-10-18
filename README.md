# AeroReach Insights: Customer Product Adoption Prediction

## Overview

This project explores how machine learning can support personalized marketing by predicting customer adoption of a travel product using demographic, behavioural, travel-related, and social media engagement data.

It was developed as an MBA capstone project in Data Science and Analytics.

## Objectives

- Explore customer characteristics and engagement patterns through exploratory data analysis.
- Identify customer segments using K-Means clustering.
- Compare multiple classification algorithms for predicting product adoption.
- Evaluate the selected model using appropriate classification metrics.
- Discuss how predictive analytics could support targeted marketing decisions.

## Dataset

The dataset contains 11,760 customer records and 17 original variables. The target variable is `Product_Taken`, representing whether a customer took the product.

## Methodology

1. Data inspection and exploratory data analysis.
2. Data cleaning and categorical encoding.
3. K-Means customer segmentation.
4. Train-test splitting.
5. Comparison of Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, and Extra Trees.
6. Class-imbalance handling with SMOTENC.
7. Numerical feature scaling using MinMaxScaler.
8. Final model evaluation using accuracy, precision, recall, F1-score, and a confusion matrix.

## Model

The Extra Trees Classifier was selected for further refinement after comparing the initial classification models.

## Business Application

Predictions could help marketing teams prioritize customer segments for relevant travel offers. Model predictions are decision-support signals, not guarantees of individual purchasing behaviour.

## Limitations

- The results depend on dataset quality and representativeness.
- Predictive associations do not establish causation.
- The model requires further validation on clean, independent data before real-world deployment.
- The project has not been deployed as a production marketing system.

## Tools

Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn, and imbalanced-learn.
