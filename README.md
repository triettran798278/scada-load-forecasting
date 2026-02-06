# SCADA Load Forecasting (1-Hour Ahead)

This repository contains my thesis project on **short-term electric load forecasting**
for an industrial plant using **SCADA time-series data** and machine learning models.

## 🎯 Objective
Predict the power consumption of an industrial plant **1 hour ahead** to support
energy management and operational planning.

## 📊 Data Source
- Industrial energy SCADA system measurements
- Time-series variables (power, voltage, current, etc.)

## ⚙️ Methods
The forecasting pipeline includes:

- Data preprocessing and cleaning
- Feature engineering (lag features, rolling statistics, time features)
- Machine learning models:
  - Random Forest
  - XGBoost (baseline)
- Deep learning models:
  - LSTM (advanced)

## 📈 Evaluation Metrics
- MAE
- RMSE
- MAPE

## 📂 Repository Structure
data/           # SCADA dataset (not uploaded if confidential)

notebooks/      # Experiments and exploration

src/            # Training and forecasting scripts

results/        # Model outputs and evaluation
docs/           # Thesis notes and references
