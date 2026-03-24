# Practical 06 – Artificial Neural Network (ANN)

## Aim
To implement an Artificial Neural Network (ANN) model for classification and evaluate its predictive performance.

## Objective
- Understand the concept of Artificial Neural Networks.
- Learn how neural networks model complex relationships in data.
- Design and train an ANN for classification.
- Evaluate model performance using accuracy and classification metrics.
- Understand the importance of feature scaling in ANN.

## Theory

Artificial Neural Network (ANN) is a deep learning model inspired by the human brain. It consists of interconnected layers of neurons:

- Input Layer – receives input features
- Hidden Layers – process data using weights and activation functions
- Output Layer – produces final predictions

Key components:
- **Activation Function (ReLU, Sigmoid)** – introduces non-linearity
- **Loss Function** – measures model error
- **Optimizer (Adam)** – updates weights to minimize loss

ANNs are powerful for capturing complex, non-linear relationships in data.

## Description

In this practical:
- Customer churn dataset is loaded
- Data preprocessing is performed (encoding + scaling)
- Dataset is split into training and testing sets
- ANN model is designed using TensorFlow/Keras
- Model is trained on training data
- Predictions are made on test data
- Model performance is evaluated

## Steps Performed

1. Import required libraries
2. Load dataset
3. Perform data preprocessing
4. Apply feature scaling
5. Split dataset into training and testing sets
6. Build ANN model
7. Train the model
8. Predict results
9. Evaluate performance

## Tools Used
- Python
- Google Colab / Jupyter Notebook
- TensorFlow / Keras
- Scikit-learn
- Pandas, NumPy

## Output

- Model accuracy
- Loss and accuracy curves
- Classification metrics

## Conclusion

Artificial Neural Networks are powerful models capable of learning complex patterns. Proper preprocessing, scaling, and architecture selection significantly improve performance.

## References
- https://en.wikipedia.org/wiki/Artificial_neural_network
- https://www.sciencedirect.com/topics/artificial-neural-network
