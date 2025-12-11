# Netflix Stock Price Prediction

## 📌 Overview
This project focuses on forecasting Netflix daily closing stock prices using advanced Time-Series Analysis. By analyzing historical financial data, the model aims to provide accurate short-term price predictions to aid investment decision-making.

## Methodology & Features
* **Data Preprocessing:** Handled non-stationary data using **Box-Cox Transformation** and **Differencing** (validated via ADF Test).
* **Modeling:** Implemented **ARIMA(1,1,0)** algorithm.
* **Optimization:** Utilized **Grid Search** for automated hyperparameter tuning.
* **Validation:** Applied **Rolling Forecast (Walk-Forward Validation)** strategy to simulate real-world trading scenarios.

## Results
The model achieved high accuracy with the following metrics:
* **MAPE (Mean Absolute Percentage Error):** **1.53%** 

<img width="854" height="476" alt="Image" src="https://github.com/user-attachments/assets/7dd63ac5-b35c-4299-9045-8f709cc71ed5" />
*(Figure: Comparison between Actual Price vs Predicted Price)*

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn.

* Author,
* Giani Alifia
* Linkedin: www.linkedin.com/in/giani-alifia
