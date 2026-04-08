Indoor CO₂ Prediction using Machine Learning
Overview

This project focuses on predicting indoor CO₂ concentration levels using environmental parameters such as temperature, humidity, light, and occupancy. Multiple machine learning models are implemented and compared to identify the most effective approach for capturing non-linear relationships in indoor air quality data.

Dataset

The dataset consists of real-time indoor environmental measurements including:

Temperature
Humidity
Light intensity
Occupancy
CO₂ concentration (target variable)

Basic preprocessing steps such as removing unnecessary columns and handling data structure were performed before training.

Methodology
Split dataset into training and testing sets
Applied multiple regression models:
Linear Regression
Decision Tree Regressor
Gradient Boosting Regressor
Random Forest Regressor
Performed hyperparameter tuning using GridSearchCV
Evaluated models using R² score
Results
Linear Regression showed low performance due to non-linear data patterns
Decision Tree significantly improved prediction accuracy
Gradient Boosting achieved strong performance
Random Forest provided the best results with highest accuracy
Features
Handles non-linear relationships in environmental data
Compares multiple ML algorithms
Hyperparameter tuning for improved performance
Predicts CO₂ levels based on real-time inputs
Technologies Used
Python
Pandas, NumPy
Scikit-learn
Jupyter Notebook
Usage
Input environmental parameters:
Temperature
Humidity
Light
Occupancy
The trained model predicts CO₂ concentration based on inputs.
Future Improvements
Use real-time sensor integration
Deploy model as a web or IoT application
Improve accuracy using advanced ensemble models
