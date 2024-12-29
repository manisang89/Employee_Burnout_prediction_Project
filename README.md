# Employee Burnout Analysis and Prediction

## Project Overview
This project focuses on analyzing and predicting employee burnout using various machine learning models, including Linear Regression and K-Nearest Neighbors (KNN) Regression. Employee burnout is a critical issue that can significantly affect productivity, job satisfaction, and overall organizational performance. By analyzing various factors such as workload, gender, and work-from-home setup, this project aims to predict burnout levels and help organizations take preventive measures.

## Objective
The primary goal of this project is to predict employee burnout based on various features, including:

- **Workplace Features:** Work-from-home availability, company type, and employee gender
- **Work Performance:** Metrics like resource allocation, mental fatigue, and burn rate

The project uses Linear Regression and K-Nearest Neighbors (KNN) Regression models to analyze the data and predict burnout levels.

## Dataset
The dataset used in this project contains employee information, including demographic data and performance metrics. Key features include:

- **Company_Type:** Type of company the employee works at
- **Gender:** Gender of the employee
- **WFH_Setup_Available:** Whether the employee has a work-from-home setup
- **Burn_Rate:** A metric indicating the level of burnout
- **Mental_Fatigue:** A measure of how mentally fatigued the employee is
- **Resource_Allocation:** The amount of resources allocated to the employee's work
- **Date_of_Joining:** The employee's date of joining, used for calculating seniority

## Machine Learning Models
The following machine learning models are used to predict employee burnout:

- **Linear Regression:** A simple approach that models the relationship between the target variable (burnout) and the input features using a linear function.
- **K-Nearest Neighbors (KNN) Regression:** A non-parametric method that predicts the target variable based on the average value of the nearest neighbors in the feature space.

## Steps Involved

### Data Preprocessing:
- Cleaning the dataset by handling missing values, categorical variables, and outliers.
- Feature engineering, including transforming the date of joining to a numerical value representing seniority.
- Splitting the data into training and testing sets.

### Model Training:
- **Linear Regression:** The model is trained on the training set and predictions are made.
- **KNN Regression:** The model is trained with a specified number of neighbors and predictions are made.

### Model Evaluation:
- Performance metrics such as Mean Squared Error (MSE), R-Squared, and Root Mean Squared Error (RMSE) are used to evaluate the model's performance on the test set.

### Visualization:
- Plots of actual vs. predicted burnout values to assess the accuracy of the predictions.
- Feature importance analysis to understand the impact of different variables on burnout levels.

## Performance Metrics
The following performance metrics are used to evaluate the models:

- **Mean Squared Error (MSE):** Measures the average squared difference between the predicted and actual values.
- **Root Mean Squared Error (RMSE):** The square root of MSE, providing error magnitude in the same units as the target variable.
- **R-Squared (R²):** Represents the proportion of variance in the target variable that is explained by the model.
