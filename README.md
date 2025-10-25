# Predicting Bank Customer Churn

## Summary
This project develops a machine learning model to predict bank customer churn, based on demographics and banking relationships, building robust data processing and trained a Logistic Regression to identify customers who are at high risk of leaving the bank

## Problem
1. Targeting loyal customers with unncessary retention offers
2. Failing to engage high risk customers before they make decision to leave

## Methodology
1. EDA and Data Preprocessing (cehcking missing values, distribution of gender, demographics, churn)
2. Encoding (country and gender)
3. Normalization
4. Modeling
5. Evaluate
6. Fine Tuning
   
## Skills
1. Python: Pandas, Numpy, Matplotlib/Seaborn
2. Data Preprocessing: Pipeline, StandardScaler, OneHotEncoder, SimpleImputer
3. Modeling: LogisticRegression
4. Finetuning: GridSearchCV

Results
1. The Final model achieving cross validation accuracy of 81.09% and test set accuracy 81.20%

Next Steps:
1. Try advanced models such as Randoom Forest, XGBoost that might capture mnore complex non linear patterns
2. Featuree Engineering with existing data to provide stronger predictive signals
