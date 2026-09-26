# Forest Fires Data Analysis and Prediction

## Project Overview

This project analyzes the UCI Forest Fires dataset to understand factors associated with forest fire behavior and build predictive models for burned area and fire classification.

## Objectives

* Explore relationships between environmental variables and burned area.
* Build and compare regression models.
* Apply Ridge and Lasso regularization.
* Build a logistic regression classification model.
* Evaluate model performance and diagnostics.
* Check for multicollinearity using VIF.

## Methods

* Exploratory Data Analysis
* Linear Regression
* Extended Regression
* Ridge Regression
* Lasso Regression
* Logistic Regression
* Residual Diagnostics
* Q-Q Plot
* Cook's Distance
* Variance Inflation Factor (VIF)

## Key Results

| Model / Metric     |    Result |
| ------------------ | --------: |
| Ridge Test MSE     | 11,759.70 |
| Lasso Test MSE     | 11,762.49 |
| Logistic Accuracy  |    54.81% |
| Logistic Precision |    54.29% |
| Logistic Recall    |    71.70% |
| Logistic F1-Score  |    61.79% |

## Key Findings

Ridge regression produced a slightly lower test MSE than Lasso. Logistic regression achieved 54.81% accuracy and 71.70% recall when classifying observations based on above-median burned area.

The VIF results showed that all predictors had values below 5, indicating no serious multicollinearity.

## Conclusion

The analysis demonstrates how different statistical and machine learning models can be used to analyze forest fire behavior. The results also highlight the trade-off between model simplicity, interpretability, and predictive performance.

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Statsmodels
* Google Colab
* GitHub
