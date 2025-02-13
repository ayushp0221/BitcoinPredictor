# Bitcoin Price Prediction

## Overview
This project aims to develop and validate a robust machine learning model for forecasting Bitcoin price trends. By leveraging historical price data, market sentiment, and financial indicators, the model provides actionable insights for investors, analysts, and cryptocurrency enthusiasts.

## Objective
The primary goal is to predict short-term and long-term Bitcoin price movements using advanced Deep learning models.

## Dataset
- **Size**: 26 million records of Bitcoin price data
- **Source**: [Kaggle - BTC in USD](https://www.kaggle.com/datasets/prasoonkottarathil/btcinusd?select=BTC-2018min.csv)
- **Features Used**: Index, Values
- **Split**: 80% training data, 20% test data

## Model Selection & Training
- **LSTM (Long Short-Term Memory)**: Captures long-term dependencies in time series data.
- **Bidirectional LSTM (Bi-LSTM)**: Processes data in both forward and backward directions to leverage all available information.
- **GRU (Gated Recurrent Units)**: A computationally efficient alternative to LSTM, reducing training time while maintaining accuracy.

## Results & Achievements
- Comparative analysis of models with and without data scaling.
- **Bidirectional LSTM** achieved the best performance in terms of accuracy and consistency.
- Potential improvements include incorporating additional data sources and ensemble learning techniques.

## Future Work
- Further fine-tuning of hyperparameters.
- Experimenting with different feature engineering techniques.
- Exploring other time-series forecasting models such as Transformer-based architectures.
