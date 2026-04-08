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


