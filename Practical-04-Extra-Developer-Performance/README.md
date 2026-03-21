# Extra Practical 04 – Decision Tree Regression

## Aim
To implement a Decision Tree regression model on the Developer Performance dataset and analyze how different tree depths and splitting criteria influence model performance.

## Objective
- Understand Decision Tree regression.
- Learn how trees predict continuous values.
- Analyze effect of model parameters on performance.
- Evaluate regression model using appropriate metrics.

## Theory

Decision Tree Regression predicts continuous values by splitting data into regions and assigning average values to each region.

Unlike classification trees:
- Output is numeric
- Uses variance reduction instead of entropy

Key parameters:
- max_depth
- min_samples_split
- criterion (squared_error)

## Description

In this practical:
- Developer Performance dataset is loaded
- Data preprocessing is performed
- Decision Tree Regressor is trained
- Predictions are generated
- Model performance is evaluated using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score

Different tree depths are tested to observe performance changes.

## Steps Performed

1. Import libraries
2. Load dataset
3. Preprocess data
4. Split dataset
5. Train Decision Tree Regressor
6. Predict outputs
7. Evaluate model
8. Compare results

## Tools Used
- Python
- Scikit-learn
- Pandas, NumPy

## Output

- Predicted values
- Error metrics (MAE, MSE, R²)

## Conclusion

Decision Tree Regression is useful for predicting continuous values. However, deeper trees may lead to overfitting. Proper tuning improves performance.

## References
- https://scikit-learn.org/stable/modules/tree.html
