# Predictive Modeling and Production Optimization

## Project Overview
This project aims to predict daily product demand using historical sales data and optimize production scheduling based on these predictions using machine learning and optimization techniques.
## Introduction
The project consists of two main parts:

1. Prediction Problem: Forecast daily demand for a product using historical sales data.
2. Optimization Problem: Optimize the production schedule to minimize total production cost while meeting the predicted demand and adhering to operational constraints.
## Steps
1. **Data Preparation**
    - Load historical sales data.
    - Extract date features: `Month` and `Day_of_week`.

2. **Machine Learning Models**
    - Models: Random Forest Regressor (RFR), Gradient Boosting Regressor (GBR).
    - Hyperparameter tuning using GridSearchCV.

3. **Ensemble Learning**
    - Combine predictions from RFR and GBR using simple averaging.

4. **Optimization Problem**
    - Use Gurobi to minimize production cost while meeting demand.
    - Define objective and constraints.

## Dependencies
- pandas
- numpy
- scikit-learn
- gurobipy

Install dependencies:
```bash
pip install pandas numpy scikit-learn gurobipy
```
## Usage

### Clone the Repository:
```bash
git clone https://github.com/akhil0203/prediction-and-optimisation.git
cd predictive-modeling-optimization
```
