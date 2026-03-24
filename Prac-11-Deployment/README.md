# Practical 11: Machine Learning Model Deployment

## Aim
To deploy a trained machine learning model using a suitable framework or platform and test it with real-time or unseen data.

## Objective
- Understand the process of deploying ML models in real-world applications
- Learn how to convert trained models into production-ready systems
- Implement deployment using Flask API
- Test model with real-time input data
- Understand performance and scalability considerations

## Description
This practical demonstrates the deployment of a machine learning model using Flask. The model is trained on the Iris dataset and deployed as a web application that can take user input and return predictions in real time.

The deployment process includes:

- Training a machine learning model
- Saving the model using joblib (model serialization)
- Creating a Flask API for handling requests
- Loading the trained model in the backend
- Accepting user input through API or web interface
- Returning predictions dynamically

The project is deployed using Render, making it accessible globally.

## Deployment Architecture
User Input → Flask API → Preprocessing → Model → Prediction → Output

## Technologies Used
- Python
- Flask
- Scikit-learn
- Joblib
- Render (Cloud Deployment)

## Project Repository
[View Deployment Project](https://github.com/tishamondal-stargazer/iris-ml-deployment)

## Live Deployment
[Live App](https://iris-app-r88q.onrender.com)

## Output
- Real-time predictions using web interface
- API-based predictions

## Conclusion
Model deployment is a crucial step in the machine learning lifecycle. This practical demonstrates how a trained model can be converted into a real-world application accessible to users.

## Author
Tisha Mondal
