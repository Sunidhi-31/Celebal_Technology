# Celebal_Technology
Data Science Internship Weekly Task
Final Project:-
# Multi-Series Forecasting for Retail Demand Optimization

## Overview
This project focuses on forecasting daily retail demand across multiple store-item combinations using historical sales data. The objective is to predict future sales by capturing temporal patterns, seasonality, and demand trends to support inventory and supply chain optimization.

## Dataset
The dataset contains five years of daily sales data for:
- 10 Stores
- 50 Items
- Daily Sales Records

## Project Workflow
- Data Loading and Inspection
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Engineering
- Baseline Forecasting Model
- LightGBM Model Training
- Model Evaluation
- Feature Importance Analysis
- Prediction Performance Visualization

## Features Used
- Store ID
- Item ID
- Year, Month, Day
- Day of Week
- Week of Year
- Quarter
- Lag Features
- Rolling Mean Features
- Rolling Standard Deviation
- Expanding Mean

## Model
- Baseline Model (Previous Day Sales)
- LightGBM Regressor

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Symmetric Mean Absolute Percentage Error (SMAPE)

## Results

| Model | MAE | SMAPE |
|-------|------:|------:|
| Baseline | 11.24 | 21.12% |
| LightGBM | 6.01 | 11.90% |

The LightGBM model significantly outperformed the baseline model, demonstrating the effectiveness of feature engineering for retail demand forecasting.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- LightGBM
- Google Colab

## Future Work
Future improvements include recursive multi-step forecasting, hyperparameter tuning, and comparison with advanced forecasting models such as XGBoost, Prophet, and LSTM.
