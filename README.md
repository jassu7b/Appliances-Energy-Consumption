# Predicting Appliances Energy Consumption 

## Project Overview

This project aims to predict household appliance energy consumption using Machine Learning techniques and environmental sensor data. The objective is to develop an accurate predictive model that can help optimize energy usage, reduce electricity costs, and support energy-efficient decision-making in smart homes.

## Problem Statement

With the growing demand for energy efficiency, accurately forecasting appliance energy consumption has become increasingly important. This project leverages indoor and outdoor environmental factors to predict energy usage and identify the variables that significantly influence household energy consumption.

## Dataset

The dataset contains appliance energy consumption records along with environmental and weather-related features. Detailed descrption of the dataset with respect to columns is given in the "description.txt" .

## Project Workflow

### 1. Data Collection

* Imported and examined the appliance energy consumption dataset.
* Verified data quality and feature consistency.

### 2. Data Preprocessing

* Handled missing values and outliers.
* Removed duplicate records.
* Performed feature scaling and transformation where required.

### 3. Exploratory Data Analysis (EDA)

* Analyzed energy consumption patterns over time.
* Investigated relationships between environmental variables and energy usage.
* Visualized trends and correlations using statistical plots and charts.

### 4. Feature Engineering

* Selected the most relevant features affecting energy consumption.
* Generated additional time-based and derived features to improve model performance.

### 5. Model Development

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor

### 6. Hyperparameter Tuning

* Applied GridSearchCV for model optimization.
* Improved model accuracy and generalization capability.

### 7. Model Evaluation

Evaluated models using:

* R² Score
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* SHAP

## Author

Bhoday Jasmeet Singh | Computer Science Graduate | Machine Learning & Data Analytics Enthusiast
