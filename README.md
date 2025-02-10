# Real-Estate-Price-Prediction-OLS

# 📊 Ordinary Least Squares (OLS) Regression

This project implements an Ordinary Least Squares (OLS) Regression model to predict real estate prices based on square footage. The dataset contains property listings from San Luis Obispo County, and the model estimates house prices by minimizing the Residual Sum of Squares (RSS).

# Dataset
The dataset consists of real estate listings with the following fields:

*MLS – Unique identifier for the listing

*Price – Listing price (in USD)

*Bedrooms – Number of bedrooms

*Bathrooms – Number of bathrooms

*Size – House size (square feet)

*Price/SQ.ft – Price per square foot

# For this project, we focus on Size (square footage) as the primary feature to predict house prices.

# ⚙️ Implementation Details

1. Data Preprocessing

*Feature Scaling: Min-Max Normalization applied to standardize square footage.

*Data Splitting: Dataset divided into training and testing sets.

2. Model Training: Ordinary Least Squares (OLS)

*Normal Equation: The optimal weight vector w is computed using:

<img width="194" alt="Screenshot 2025-02-10 at 10 41 44 AM" src="https://github.com/user-attachments/assets/6f2c9f61-f2ec-448e-bac7-f526937016f0" />

*Regression Line: The model learns a linear function mapping square footage to price.

# 📊 Results

📉 Regression Line Plot

<img width="583" alt="Screenshot 2025-02-10 at 10 37 37 AM" src="https://github.com/user-attachments/assets/6243c436-07d7-49fe-bf39-600d961c77e1" />

A visualization of the OLS regression line fitted over training data.

# 🏡 Price Prediction Example

Example: Estimated price for a 5000 sq. ft. house (after normalizing input).
