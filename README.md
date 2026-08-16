**AI-Based Smart Energy Consumption Prediction and Optimization Using IoT Sensor Analytics**

## Overview

This repository contains the implementation of an MSc Data Science individual research project focused on household electricity consumption forecasting.

The project investigates machine learning and deep learning techniques for predicting electricity consumption, analysing consumption patterns, identifying peak-demand periods, interpreting model predictions, and assessing prediction uncertainty.

## Objectives

The main objectives of the project are:

- Analyse household electricity consumption data.
- Identify important temporal and consumption-related patterns.
- Develop machine learning and deep learning models for energy forecasting.
- Compare the performance of different forecasting models.
- Evaluate forecasting performance using appropriate time-series methods.
- Analyse peak-demand prediction performance.
- Identify important features influencing energy consumption.
- Apply SHAP for Explainable AI.
- Assess prediction uncertainty using conformal prediction.

## Methodology

The research follows these main stages:

1. Data loading and inspection
2. Data cleaning and preprocessing
3. Exploratory Data Analysis
4. Time-series aggregation
5. Feature engineering
6. Baseline modelling
7. Machine learning modelling
8. Deep learning modelling
9. Model comparison
10. Walk-forward validation
11. Feature ablation analysis
12. Statistical evaluation
13. SHAP explainability analysis
14. Prediction uncertainty analysis
15. Results visualisation

## Models

The following models were developed and evaluated:

- Linear Regression
- Random Forest
- XGBoost
- LightGBM
- Long Short-Term Memory (LSTM)

Hyperparameter optimisation was also performed using Optuna.

## Feature Engineering

The project uses time-series and historical consumption features, including:

- Hour and date-based features
- Lag features
- Rolling-window features
- Cyclical time features
- Historical consumption patterns

## Model Evaluation

Models were evaluated using:

- RMSE
- MAE
- R²

Additional evaluation included:

- Walk-forward validation
- Residual analysis
- Peak-demand analysis
- Feature ablation
- Statistical comparison
- Bootstrap confidence intervals

## Explainable AI

SHAP (SHapley Additive exPlanations) was used to analyse the contribution of individual features to model predictions.

This provides greater transparency and helps identify the factors that have the greatest influence on electricity consumption forecasts.

## Uncertainty Analysis

Conformal prediction was used to assess prediction uncertainty and provide prediction intervals alongside point forecasts.

This allows forecast reliability to be evaluated in addition to conventional prediction accuracy.

## Dataset

The project uses a publicly available household electricity consumption dataset.

The raw dataset is not included in this repository where redistribution restrictions may apply. The notebook contains the data-loading and preprocessing workflow required to reproduce the analysis after obtaining the dataset from its original source.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- LightGBM
- TensorFlow / Keras
- SHAP
- Optuna
- Streamlit

## Repository Contents

```text
AI-Based-Smart-Energy-Consumption-Prediction/
│
├── README.md
│
└── smart_energy_consumption_forecasting.ipynb

## Author

**Manohar Prabhu Hiremath**

MSc Data Science  
Coventry University
