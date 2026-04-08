# Indoor CO₂ Prediction using Machine Learning

## Project Overview
This project predicts indoor CO₂ concentration using environmental factors such as temperature, humidity, light, and occupancy. Multiple machine learning models are implemented and compared to identify the most effective approach.

## Objective
To build a predictive model that estimates CO₂ levels based on indoor environmental conditions and evaluate different regression algorithms.

## Dataset
The dataset includes:
- Temperature
- Humidity
- Light
- Occupancy
- CO₂ (target variable)

Basic preprocessing was performed before training.

## Models Used
- Linear Regression
- Decision Tree Regressor
- Gradient Boosting Regressor
- Random Forest Regressor

## Model Evaluation
- Metric used: R² Score
- Hyperparameter tuning using GridSearchCV
- Performance comparison across models

## Results
- Linear Regression: Low performance
- Decision Tree: Improved accuracy
- Gradient Boosting: Good performance
- Random Forest: Best performance

## Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook

## How to Run
1. Load the dataset
2. Train the model using the provided code
3. Enter input values:
   - Temperature
   - Humidity
   - Light
   - Occupancy
4. Get predicted CO₂ output

## Future Scope
- Real-time sensor integration
- Model deployment
- Further optimization using advanced techniquesIndoor CO₂ Prediction using Machine Learning
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
