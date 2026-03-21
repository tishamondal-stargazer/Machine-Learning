# Practical 04 – Decision Tree Classification

## Aim
To build and evaluate a Decision Tree model for classification tasks and study the effect of tree depth and splitting criteria.

## Objective
- Understand the working of Decision Tree algorithm.
- Learn how decision trees split data using different criteria.
- Study the impact of tree depth on model performance.
- Evaluate classification models using metrics like accuracy and confusion matrix.
- Analyze overfitting and underfitting in decision trees.

## Theory

Decision Tree is a supervised machine learning algorithm used for classification and regression tasks. It works by splitting the dataset into subsets based on feature values.

A decision tree consists of:
- Root Node – starting point of the tree
- Decision Nodes – where data splits occur
- Leaf Nodes – final output or class labels

### Key Concepts:
- **Entropy** – measure of randomness
- **Information Gain** – reduction in entropy after split
- **Gini Index** – impurity measure used in CART
- **Max Depth** – controls tree complexity

Decision Trees are easy to interpret and mimic human decision-making.

## Description

In this practical:
- Dataset is loaded and preprocessed
- Data is split into training and testing sets
- Decision Tree model is trained using sklearn
- Predictions are made on test data
- Model performance is evaluated using:
  - Accuracy
  - Confusion Matrix
  - Classification Report

The effect of different parameters like `max_depth` and `criterion` is also analyzed.

## Steps Performed

1. Import required libraries
2. Load dataset
3. Perform preprocessing (if required)
4. Split dataset into training and testing sets
5. Train Decision Tree classifier
6. Make predictions
7. Evaluate model performance
8. Analyze results

## Tools Used
- Python
- Google Colab / Jupyter Notebook
- Scikit-learn
- Pandas, NumPy, Matplotlib

## Output

- Model accuracy score
- Confusion matrix
- Classification report

## Conclusion

Decision Tree is an intuitive and powerful algorithm for classification tasks. It performs well on structured data and provides clear decision rules. However, deep trees may overfit, so parameters like max_depth must be controlled.

## References
- https://www.kdnuggets.com/2020/01/decision-tree-algorithm-explained.html
- https://www.mastersindatascience.org/learning/machine-learning-algorithms/decision-tree/
