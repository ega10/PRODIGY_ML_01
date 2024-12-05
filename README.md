# PRODIGY_ML_01
This is my Prodigy Infotech intern's first task
# House Price Prediction using Linear Regression

This project implements a **Linear Regression** model to predict house prices based on features such as **square footage**, **number of bedrooms**, and **number of bathrooms**. The dataset includes other relevant features like `sqft_living`, `bedrooms`, `bathrooms`, etc., but we focus on the key predictors for this model.

## Project Overview

- **Objective**: Predict house prices based on features like square footage, number of bedrooms, and bathrooms.
- **Algorithm**: Linear Regression
- **Data**: A real estate dataset containing various features related to house sales.

## Features Used:
- `sqft_living`: Square footage of the living space.
- `bedrooms`: Number of bedrooms in the house.
- `bathrooms`: Number of bathrooms in the house.

## Steps Involved:
1. **Data Preprocessing**:
   - Load the CSV data.
   - Drop irrelevant columns (`date`, `street`, `city`, etc.).
   - Handle missing data by removing rows with null values.
   
2. **Model Training**:
   - Split the data into training and testing sets (80% train, 20% test).
   - Train a linear regression model using features (`sqft_living`, `bedrooms`, `bathrooms`).

3. **Model Evaluation**:
   - Evaluate the model using metrics like **Mean Squared Error (MSE)** and **R-squared**.

4. **Visualization**:
   - Scatter plots for the relationship between features and house prices.
   - Predicted vs Actual Prices plot.
   - Coefficients visualization to understand the impact of each feature on the price.

## Required Libraries:
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## How to Run:
1. Install the required libraries:
2. Load dataset and run it
