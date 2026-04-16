# Hotel No Show
Supervised training: Classification

**Problem Statement: Predict the no-show of customers not showing up to help hotel formulate policies to reduce expenses incurred due to no-show.**

## EDA 
1. Summarise dataset, and understand the distribution of all features and the relationship they have with the target variable (no-show). 
2. Likely to find class imbalance. 

## Data preprocessing 
1. Review missing data, and if few, impute mean/median for numerical values, and mode for categorical values. 
2. Ensure consistent formatting of data and ensure alignment of datatypes with variable intent e.g. booking month should be categorical and not numerically recorded.

## Feature engineering
1. Add relevant features: length of stay, total cost of stay, total number of people, cost of stay per day per person. 
2. Scale price, number of people. 

# Splitting of data
1. Split training and test data to prevent data leakage. 

## Modelling 
1. Logistic regression to understand baseline, and high interpretability.  
2. Decision tree to identify non-linear patterns.  
3. Random Forest to avoid overfitting of decision tree. 

## Evaluation
1. Evaluate model performance via accuracy, precision, and recall. 