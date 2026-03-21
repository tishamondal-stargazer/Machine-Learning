# Practical 05 – Random Forest Classification

## Aim
To implement the Random Forest algorithm and evaluate the model performance using appropriate metrics.

## Objective
- Understand ensemble learning concepts
- Learn how Random Forest improves over Decision Trees
- Train and evaluate Random Forest classifier
- Analyze model performance

## Theory

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve accuracy and reduce overfitting.

It works using:
- Bagging (Bootstrap Sampling)
- Feature Randomness

Each tree makes predictions, and final output is based on majority voting.

Advantages:
- Reduces overfitting
- Handles large datasets
- Provides feature importance

## Description

In this practical:
- Dataset is loaded and explored
- Data preprocessing is applied
- Random Forest model is trained
- Predictions are made
- Performance is evaluated using:
  - Accuracy
  - Confusion Matrix
  - Classification Report

## Steps Performed

1. Import libraries
2. Load dataset
3. Preprocess data
4. Split dataset
5. Train Random Forest model
6. Predict outcomes
7. Evaluate performance

## Tools Used
- Python
- Scikit-learn
- Pandas, NumPy

## Output

- Accuracy score
- Confusion matrix
- Classification report

## Conclusion

Random Forest improves prediction accuracy by combining multiple trees. It reduces overfitting and performs well on complex datasets.

## References
- https://www.ibm.com/topics/random-forest
- https://www.analyticsvidhya.com/blog/2021/05/bagging-25-questions-to-test-your-skills-on-random-forest-algorithm/
