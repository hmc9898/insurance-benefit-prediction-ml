# Insurance Benefit Prediction with Machine Learning

## Project Overview

This project was developed for Sure Tomorrow, a fictional insurance company, to explore the use of machine learning in optimizing customer targeting and benefit prediction. The workflow includes classification, regression, customer similarity analysis, and data masking to ensure model robustness while protecting personal data.

## Objectives

- Identify customers most similar to a target individual (for marketing outreach)  
- Predict whether a new customer will receive insurance benefits  
- Estimate the number of benefits a customer is likely to receive  
- Implement a secure data transformation method to obfuscate personal data without degrading model quality

## Tools & Technologies

- Python  
- pandas, NumPy  
- scikit-learn  
- matplotlib, seaborn  
- Custom implementation of Linear Regression  
- Jupyter Notebook

## Approach

- Performed exploratory analysis and feature scaling  
- Applied k-Nearest Neighbors for similarity-based recommendations  
- Built classification and regression models using logistic and linear regression  
- Compared models to dummy baselines using F1, RMSE, and R²  
- Demonstrated that linear regression performance is invariant under a custom linear data transformation

## Key Insights

- Classification models significantly outperformed baseline predictions  
- Regression models achieved high accuracy in estimating benefit amounts  
- The custom data masking transformation successfully protected features without impacting model performance

## Author

Heather Marie Culligan  
[LinkedIn](https://linkedin.com/in/hmc2025)  
[GitHub](https://github.com/hmc9898)
