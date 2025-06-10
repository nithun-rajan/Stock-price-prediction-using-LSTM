# Stock-price-prediction-using-LSTM
This repository hosts a Python project for predicting stock prices of Tata Global Beverages Limited (NSE: TATAGLOBAL) using an LSTM neural network built with TensorFlow/Keras.

# Stock Price Prediction with LSTM

This project implements a Long Short-Term Memory (LSTM) neural network to predict stock prices for Tata Global Beverages Limited (NSE: TATAGLOBAL) using historical stock data. The Python script preprocesses the data, trains an LSTM model, generates predictions, and visualizes the results as plots or interactive HTML output viewable in browsers like Safari. The project demonstrates time-series forecasting with deep learning, including data normalization, model persistence, and visualization options using `matplotlib`, `plotly`, or `mpld3`. Ideal for those interested in financial modeling, machine learning, or data science.

## Features

- **Data Preprocessing**: Loads and processes historical stock data (`Date` and `Close` prices) using `pandas`, with normalization via `MinMaxScaler` from `scikit-learn`.
- **LSTM Model**: Builds a sequential LSTM model with `TensorFlow`/`Keras` to capture temporal patterns for stock price prediction.
- **Visualization**: Generates plots comparing actual and predicted closing prices using `matplotlib`. Optional HTML output is supported with `plotly` or `mpld3` for interactive browser viewing (e.g., Safari on macOS).
- **Model Persistence**: Saves the trained LSTM model as `saved_model.h5` for reuse.
- **Automated Browser Integration**: Includes functionality to save plots as HTML and automatically open them in Safari using `os.system`.
- **Error Handling**: Addresses common issues like `Timestamp` errors in data preprocessing for robust execution.

## Requirements

- Python 3.6+
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `tensorflow`
  - `scikit-learn`
  - `plotly` (optional, for interactive HTML plots)
  - `mpld3` (optional, for converting matplotlib plots to HTML)
- Dataset: `NSE-Tata-Global-Beverages-Limited.csv` (must include `Date` and `Close` columns)

