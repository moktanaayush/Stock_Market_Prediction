# Stock Market Prediction Using LSTM and Machine Learning

## Project Overview
This project aims to predict the closing price of stocks using various techniques, including **Long Short-Term Memory (LSTM)** for time series prediction and **Random Forest** and **XGBoost** for regression-based modeling.

The project uses **historical stock data** from **Nabil Bank** along with several technical indicators such as moving averages (SMA, EMA), Relative Strength Index (RSI), and others.

## Project Features
- **Data Collection**: Historical stock data including features like `high`, `low`, `close`, and transaction volume.
- **Feature Engineering**: Several technical indicators like `SMA-10`, `SMA-50`, `EMA-10`, `EMA-50`, and `RSI-14` are calculated.
- **Data Preprocessing**: Handling missing values, scaling features, and splitting data into training and test sets.
- **Modeling**:
  - **LSTM** for predicting future stock prices using time-series data.
  - **Random Forest Regressor** and **XGBoost** for regression tasks to predict stock closing prices.
- **Hyperparameter Tuning** for Random Forest and XGBoost using GridSearchCV.
  
## Requirements
To run this project locally, make sure you have the following dependencies installed:

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow (for LSTM model)
- xgboost

You can install the necessary libraries using pip:

```bash
pip install -r requirements.txt
