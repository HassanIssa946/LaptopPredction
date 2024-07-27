# Regression Model Comparison

This project involves comparing the performance of three regression models on a dataset. The models evaluated are:

- **ElasticNet**
- **DecisionTreeRegressor**
- **KNeighborsRegressor**

## Overview

The goal of this project is to evaluate and compare the performance of different regression models using Mean Absolute Error (MAE) as the evaluation metric. The dataset used for this analysis was preprocessed to prepare it for model training.

## Data Preprocessing

Before training the models, the following preprocessing steps were performed:

1. **Data Cleaning:** Handled missing values, removed duplicates, and addressed inconsistencies.
2. **Feature Engineering:** Selected relevant features and engineered new features if necessary.
3. **Feature Scaling:** Applied scaling techniques to standardize the feature values.

## Models Used

1. **ElasticNet:**
   - A linear model that combines both L1 and L2 regularization to improve model performance and handle multicollinearity.

2. **DecisionTreeRegressor:**
   - A non-linear model that splits the data based on feature values to make predictions.

3. **KNeighborsRegressor:**
   - A non-parametric model that predicts the target value based on the average of the k-nearest neighbors.

## Model Evaluation

The models were evaluated using the Mean Absolute Error (MAE) metric, which measures the average magnitude of the errors in the model's predictions. The MAE for each model is as follows:

- **ElasticNet:** MAE = 269.8659
- **DecisionTreeRegressor:** MAE = 232.9419
- **KNeighborsRegressor:** MAE = 325.5642

### Summary of Results

- **DecisionTreeRegressor** achieved the lowest MAE, indicating the best performance among the three models.
- **ElasticNet** followed with slightly higher MAE, showing reasonable performance but not as effective as the Decision Tree model.
- **KNeighborsRegressor** had the highest MAE, suggesting it was less effective in predicting the target variable compared to the other models.

## Conclusion

Based on the evaluation, the **DecisionTreeRegressor** is the most suitable model for this dataset, providing the most accurate predictions. Further tuning and validation could enhance the performance of these models.

## Future Work

- **Hyperparameter Tuning:** Explore different hyperparameters to optimize model performance.
- **Additional Models:** Consider evaluating additional regression models or advanced techniques.
- **Cross-Validation:** Implement cross-validation to ensure the robustness of model performance.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository-url>
