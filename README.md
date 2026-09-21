# Household Energy Consumption Prediction

## Project Overview

This project focuses on predicting **household energy consumption** using Machine Learning techniques.

The project analyzes household-related factors such as **household size, average temperature, and peak-hour energy usage** to predict total energy consumption in kWh.

A **Polynomial Regression** model is used to learn the relationship between these factors and household energy consumption.

## Objective

The main objectives of this project are:

* Analyze household energy consumption data.
* Understand the relationship between household characteristics and energy usage.
* Build a Machine Learning model to predict energy consumption.
* Evaluate the prediction performance of the model.
* Compare actual energy consumption with predicted values through visualization.

## Dataset

The dataset contains **90,000 household records** with information related to energy consumption and household conditions.

### Important Features

* **Household ID** – Unique identifier for each household.
* **Date** – Date of the recorded observation.
* **Energy Consumption (kWh)** – Target variable representing household energy consumption.
* **Household Size** – Number of people in the household.
* **Average Temperature (°C)** – Average temperature recorded.
* **Has AC** – Indicates whether the household has an air conditioner.
* **Peak Hours Usage (kWh)** – Energy consumed during peak hours.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab / Jupyter Notebook

## Machine Learning Approach

The project uses **Polynomial Regression** for energy consumption prediction.

The selected input features are:

* Household Size
* Average Temperature
* Peak Hours Usage

The dataset is divided into training and testing sets, followed by polynomial feature transformation and model training.

## Model Performance

The Polynomial Regression model achieved the following evaluation results:

| Metric   |  Value |
| -------- | -----: |
| MAE      | 0.5593 |
| MSE      | 0.5133 |
| RMSE     | 0.7164 |
| R² Score | 0.9831 |

These metrics are used to measure the difference between the actual and predicted energy consumption values.

## Visualization

An **Actual vs Predicted Energy Consumption** scatter plot was created to visualize the model's predictions.

The graph compares:

* **Actual Energy Consumption (kWh)**
* **Predicted Energy Consumption (kWh)**

The visualization helps examine how closely the predicted values correspond to the actual values.

## Key Learning Outcomes

This project provided practical experience in:

* Data loading and exploration
* Data preprocessing
* Feature selection
* Exploratory Data Analysis
* Train-test splitting
* Polynomial Regression
* Machine Learning prediction
* Model evaluation
* Data visualization
* Interpreting actual vs predicted values

## Future Enhancements

The project can be extended by:

* Adding more relevant household features.
* Comparing different Machine Learning algorithms.
* Developing an interactive energy consumption dashboard.
* Creating a web-based prediction application.
* Providing personalized energy-saving recommendations.

## Author

**Archana Devi M**

