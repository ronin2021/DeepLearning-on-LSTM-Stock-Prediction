# DeepLearning on LSTM Stock Prediction

We have used rolling window time series of ***Fear and Greed Index (FNG)*** and the ***Closing Price*** with the Deep Learning Recurrent Nural Networks (RNN) to predict closing price of BitCoin (BTC) to predic closing price.

## Outline
Analysis, model fit, and forcast of BTC Closing using tunable windows and LSTM (Long Short Term Memory) RNN.

## Part 1. Variable Window FNG of BitCoin to predict Closing Price of BitCoin

We have used provided .csv files to extract both the FNG and the Closing Prices of BTC in given time period to buid a data frame. From the data frame following shaping data to a variable time window form (via custom function ***window_data***) and then they underwent a 70% (Train) to 30% (Test) split to further process the data. Then these were reshaped towards a LSTM RNN model with a variable droput fraction. Model fit had 15 epochs. Model was evaluated in two different window lengths and changing epochs (settling in 15 epochs).
Evaluation metrics were obtaind as loss and a graphical output of Real vs. Predicted graph for the test data. 

## Part 2. Variable Window Closing Price of BitCoin to predict Closing Price of BitCoin

We have used provided .csv files to extract both the FNG and the Closing Prices of BTC in given time period to buid a data frame. From the data frame following shaping data to a variable time window form (via custom function ***window_data***) and then they underwent a 70% (Train) to 30% (Test) split to further process the data. Then these were reshaped towards a LSTM RNN model with a variable droput fraction. Model fit had 15 epochs. Model was evaluated in two different window lengths and changing epochs (settling in 15 epochs).
Evaluation metrics were obtaind as loss and a graphical output of Real vs. Predicted graph for the test data. 

## Model Comparison 

### Which model has a lower loss?

Lowest Loss is with the 
