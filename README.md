# Netflix Stock Price Prediction

## 📌 Overview
This project focuses on forecasting Netflix (NFLX) daily closing stock prices using advanced Time-Series Analysis. By analyzing historical financial data, the model aims to provide accurate short-term price predictions to aid investment decision-making.

## Methodology & Features
* **Data Preprocessing:** Handled non-stationary data using **Box-Cox Transformation** and **Differencing** (validated via ADF Test).
* **Modeling:** Implemented **ARIMA(1,1,0)** algorithm.
* **Optimization:** Utilized **Grid Search** for automated hyperparameter tuning.
* **Validation:** Applied **Rolling Forecast (Walk-Forward Validation)** strategy to simulate real-world trading scenarios.

## Results
The model achieved high accuracy with the following metrics:
* **MAPE (Mean Absolute Percentage Error):** **1.53%** 

![Graph Prediction](<img width="854" height="476" alt="predict netflix" src="https://github.com/user-attachments/assets/4932429d-7611-45e8-bd8a-524e9546f61c" />
)
*(Figure: Comparison between Actual Price vs Predicted Price)*

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn.
