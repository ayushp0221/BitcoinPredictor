# BitcoinPredictor

## Introduction:
This project aims to predict Bitcoin prices using historical data. We explore various machine learning models, focusing on deep learning techniques like LSTM, GRU, and Bidirectional LSTM, to forecast future price movements.

## Dependencies:
To run the Jupyter notebooks in this repository, you will need the following libraries:  
* NumPy
* Pandas
* Matplotlib
* Keras
* Scikit-learn

## Dataset:  
The dataset consists of minute-level price data of Bitcoin spanning from 2017 to 2021 (https://www.kaggle.com/datasets/prasoonkottarathil/btcinusd?select=BTC-2018min.csv). The data includes features such as open, high, low, close prices, and trading volume in BTC and USD.

## Preprocessing:
The preprocessing steps include:
* Removing unnecessary columns like Unix timestamps.
* Converting date strings to datetime objects.
* Handling missing values.
* Scaling numerical features to prepare data for neural network models.

## Exploratory Data Analysis (EDA):
The EDA process involves visualizing various aspects of Bitcoin prices and trading volumes over the years to understand trends and patterns that could influence the model's performance.

## Model Building:
Several models are built and tested in this project:
*	LSTM (Long Short-Term Memory): A type of recurrent neural network suitable for sequence prediction problems.
*	GRU (Gated Recurrent Unit): Simplified version of LSTM with fewer parameters.
*	Bidirectional LSTM: An extension of traditional LSTMs that can improve model performance on sequence classification problems.

## Evaluation:
The models are evaluated using metrics such as Mean Squared Error (MSE) and Mean Absolute Error (MAE). The evaluation section discusses the performance of each model, highlighting the Bidirectional LSTM for its superior accuracy.

## Usage:
To replicate the findings and run the notebooks:
1.	Clone the repository.
2.	Ensure you have Jupyter Notebook installed.
3.	Install all required dependencies.
4.	Run the Jupyter notebooks within the repository.

### Project Demo 
https://www.youtube.com/watch?v=4ujosI7b908&ab_channel=AyuShPrajapati
