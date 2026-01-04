# AI-Based Demand Forecasting System

## Overview
This project implements an end-to-end AI demand forecasting system similar to those used in large-scale retail and e-commerce platforms. The system predicts future product demand using historical sales data, seasonality, trends, and lag-based features.

## Problem Statement
Accurate demand forecasting is critical for inventory optimization, cost reduction, and customer satisfaction. This project focuses on predicting short-term demand at the store–item level using machine learning techniques.

## Dataset
Store Item Demand Forecasting dataset (Kaggle)

## Methodology
- Time-series aware train–validation split
- Feature engineering using lag features, rolling statistics, and calendar variables
- Baseline forecasting using naive lag method
- Model comparison using MAE, RMSE, and MAPE
- Final model selection using XGBoost

## Models Evaluated
- Naive Baseline
- Linear Regression
- XGBoost (Final Model)

## Results
XGBoost achieved the lowest forecasting error and was selected due to its balance of accuracy and computational efficiency.

## Forecasting
The model generates demand forecasts for the next 30 days at the SKU level, demonstrating real-world applicability.

## Technologies Used
Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn

## Developer
Aadi Jain
