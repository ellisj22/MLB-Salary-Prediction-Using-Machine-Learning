# MLB Salary Prediction Project

## Overview
This project predicts MLB player salaries using historical player statistics. The dataset combines batting, fielding, and salary records from 2000–2024. Multiple regression models, including Linear Regression, Random Forest, and XGBoost, were trained and evaluated to identify key factors influencing player salaries.

## Features
- **Batting metrics:** PA, AVG, OBP, SLG, OPS, HR, RBI  
- **Rate metrics:** BB_rate, K_rate, SB_per_PA  
- **Fielding metrics:** PO, A, E  
- **Player context:** age  

## Models
- Linear Regression  
- Random Forest Regressor  
- XGBoost Regressor  

## Evaluation
- Metrics: RMSE, MAE, Median Absolute Error, R², Max Error  
- Scatter plots for Actual vs Predicted salaries  
- Train/test performance to check for over/underfitting  
- Feature importance analysis for tree-based models  

## Repository Structure
MLB-Salary-Prediction-Using-Machine-Learning/
├── data/
│ └── raw/
│ ├── batting.csv
│ ├── salaries.csv
│ ├── fielding.csv
│ └── people.csv
├── notebooks/
│ └── MLB Batter Salaries.ipynb
└── README.md
