# Google Stock Price Prediction using LSTM

This project uses a Long Short-Term Memory (LSTM) neural network to predict the closing stock price of Google based on historical data.

## Description

- Historical stock data is used to train a deep learning model.
- An LSTM model is used due to its effectiveness in handling time series data.
- The model is trained to predict the next day's closing price.
- Mean Absolute Percentage Error (MAPE) is used as the evaluation metric.

## Files

- `GoogleProject.ipynb`: Main Jupyter notebook containing all code for data preprocessing, model building, training, prediction, and evaluation.
- 2 csv files containing historical stock price CSV data, split into test and training

## Requirements

- Python 3.x
- Keras
- NumPy
- pandas
- matplotlib
- scikit-learn

## How to Run

1. Install the required libraries.
2. Open the notebook `google_.ipynb` in Jupyter.
3. Run all cells to train the model and visualize predictions.

## Evaluation

The model's performance is evaluated using MAPE (Mean Absolute Percentage Error) to measure prediction accuracy.
