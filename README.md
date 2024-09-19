The objective of this case study is to determine whether an individual's income exceeds $50,000 per year based on various demographic and work-related features.

This is a supervised binary classification problem with two outcome values: '>50K' and '<=50K', referring to income levels.

Dataset used in this study: Kohavi, R. (1996). Census Income [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5GP7S.

Environment: Python 3.11.5; Jupyter Notebook Platform

Pipeline Details
The following steps were completed for this case study: Part One: Exploratory Data Analysis

Loading Census Data
Data Preparation – missing values, converting to appropriate data types, encoding target variable, displaying income distribution
Analyzing Features & Target Variable – numerical feature histograms, categorical features charts, outliers in numerical data, correlation matrix analysis, bivariate analysis parallel coordinates plot, chi-square and t-test statistical analyses, feature importance with Random Forest
Part Two: Biases Discussion

Potential Biases
Mitigating Biases
Part Three: Predictive Modeling

Data Preparation
Logistic Regression & Feature Importance
Random Forest Classifier & Feature Importance
XGBoost & Feature Importance
Support Vector Machine & Feature Importance
Cross-Validation Tests
Part Four: Overall Results
