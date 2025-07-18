# 🚗 Vehicle Fare Prediction using ML Ensemble Models

This project focuses on predicting vehicle fares based on various environmental and traffic-related parameters using advanced machine learning techniques. The model is trained on real-world data and employs ensemble models to maximize accuracy.

## 📊 Problem Statement

The goal is to predict the average fare charged by different types of vehicles (car, auto, bike) using features such as:
- Traffic volume
- Pollution levels (NO2, CO, O3)
- Humidity and Temperature
- Wind speed
- Timestamp-based features (hour, day, month)

## ⚙️ Tech Stack

- **Language**: Python
- **Environment**: Jupyter Notebook
- **Data Manipulation**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **ML Models**: Scikit-learn, XGBoost, LightGBM, CatBoost,ARIMAX,SARIMAX
- **Model Evaluation**: MAE, RMSE, R² Score

## 🧠 Models Used

- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**
- **XGBoost Regressor**
- **LightGBM Regressor**
- **CatBoost Regressor**
- **Stacking Regressor (Meta Model: Ridge)**

## 📈 Performance Metrics

Each model is evaluated using:
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

The stacked model achieves the best performance across all metrics.

## 📁 Files

- `VehicleFairPrediction.ipynb`: Main notebook with EDA, feature engineering, and model training.


