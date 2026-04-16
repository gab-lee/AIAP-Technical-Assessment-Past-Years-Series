# Student Score Prediction

**Problem Statement: Predict students' O-level mathematics examination scores to identify weaker students in order to better allocate resources to students who may require it more.**

## EDA
1. Understand the distribution of the various features, and the relationship they have with the target variable (students' score).

## Data preprocessing and cleaning
1. Deal with missing numbers. First understand the scale of missing numbers, if small, then impute mean/median for numerical values and the mode for categorical value. If missing number is sizeable, consider removing the entire feature.
2. Ensure data types are in alignment with feature. 
3. Ensure consistent formatting throughout feature.

## Feature Engineering
1. Scaling data such as hours per week. 
2. Create necessary features such as number of hours slept, number of hours awake, %hours studied/total awake time. 

## Split data
1. Split training data and the test data (final_test) to prevent data leakage. 

## Modelling 
1. Create a baseline linear regression model. 
2. Follow up with decision tree to identify any non-linear relationships. 
3. Follow up with random decision tree, to better understand how variables may affect target variable.

## Evaluation
1. Evaluate the accuracy of the model on unseen data to test for overfitting. 