Practical 08 Extra – PCA vs LDA with Logistic Regression

Aim  
To perform Principal Component Analysis (PCA) and Linear Discriminant Analysis (LDA) separately on a dataset, apply Logistic Regression on the transformed features, and compare their performance.

Description  
This practical demonstrates dimensionality reduction techniques PCA and LDA along with classification using Logistic Regression.

The Breast Cancer dataset is used for analysis. The dataset is loaded directly from GitHub using a raw dataset link.

The workflow includes:

• Importing required libraries such as NumPy, Pandas, Matplotlib and Scikit-learn  
• Loading dataset from GitHub using raw CSV link  
• Data preprocessing and feature scaling  
• Applying PCA for dimensionality reduction  
• Applying LDA for supervised dimensionality reduction  
• Training Logistic Regression models on PCA and LDA transformed data  
• Evaluating models using accuracy score and confusion matrix  
• Comparing performance of PCA-based and LDA-based models  

PCA reduces dimensionality by maximizing variance, while LDA focuses on maximizing class separability. This experiment helps understand which technique performs better for classification tasks.

Tools Used  
Python  
Google Colab  
Scikit-learn  
Matplotlib  

Dataset  
Breast Cancer Dataset (loaded from GitHub repository)

How to Run the Program  
Open the notebook in Google Colab  
Run all cells step by step  

Sample Output  
Accuracy comparison between PCA-based and LDA-based Logistic Regression models
