# StockM

- StockM uses Machine learning techniques to predict the closing stock market share prices
- StockM currently predicts the share price for the Apple Inc. stock.

## Data Processing

- Data from 1 January 2015 to 01 August 2020 will be used.
- The data is obtained from Yahoo.
- The data has High, Low, Open, Close, Volume, Adj Close indicators
- In the first part of StockM, only the closing price will be used for training.
- The share prices will be scaled between 0 and 1.
- For training closing share prices spanning 60 days will be used as features
- The 61st day will be used as the targets
- A split of 70% training, 10% validation and 20% testing will be used.

## Model construction and compilation

- The Neural Network Architechture used is the LSTM which is a variant of RNNs.
- The model currently comprises of 2 LSTM cells and 1 Dense cell at the output.

## Training

- The Mean Squared error loss function will be used.
- The Adam optimizer will be used.
- Additionally early stopping will be used to avoid having an over-fitting model.

## Testing

-
