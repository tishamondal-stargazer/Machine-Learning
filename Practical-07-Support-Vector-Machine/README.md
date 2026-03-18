Practical 07

Aim:
To apply Support Vector Machine for classification and analyze the impact of different kernels on model accuracy.

Objective:
• Understand the concept of Support Vector Machine for classification.
• Learn how hyperplanes separate classes in high-dimensional space.
• Apply different kernel functions in SVM.
• Evaluate model performance using classification metrics.

Dataset Used:
pulsar_stars.csv

Description:
This practical demonstrates the implementation of the Support Vector Machine (SVM) algorithm for solving classification problems in machine learning. SVM is a supervised learning algorithm that identifies an optimal hyperplane to separate data points belonging to different classes.

The pulsar stars dataset is used for classification, where the objective is to predict whether a star is a pulsar or not based on multiple numerical attributes.

The notebook performs the following steps:

• Importing required Python libraries for data analysis and machine learning  
• Loading and exploring the pulsar stars dataset  
• Performing data preprocessing and feature scaling  
• Splitting the dataset into training and testing sets  
• Training Support Vector Machine models using different kernels such as Linear, Polynomial, and Radial Basis Function (RBF)  
• Evaluating the model using accuracy score and classification metrics  

By comparing the performance of different kernels, this experiment demonstrates how kernel selection influences the decision boundary and classification performance in SVM models.

Tools Used:
Python  
Google Colab  
Scikit-learn
