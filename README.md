# CITIGROUP STOCK PRICE PREDICTION

## OVERVIEW
* In this project we try to predict the price of Citigroup Inc.
* In this project we make use of LSTM recurrent neural network to make time series forecasting.

## DATASET
* I downloaded this data from [yahoo_finance.](https://in.finance.yahoo.com/quote/C/history?p=C)
* I downloaded the data since 2.08.2016.
* You can access the data i used by downloading the file named CitiBank.csv. 

## ATTRIBUTES DESCRIPTION

|Column                   | Description                                              |
| --------                | ---------------                                          |
|DATE                     |	Date of the which the below details was recorded         |
|OPEN                     |	Value of the last stock that traded on a particular day  |
|HIGH                     |	Highest price the stock traded for on a particular day   |
|LOW                      |	Lowest price the stock traded for on a particular day    |
|CLOSE                    |	Value of the last stock that traded on a particular day  |
|ADJ_CLOSE                |	Closing price of the stock on a particular day           |
|VOLUME                   |	Amount of stock bought or sold on a particular day       |

## TECHNIQUES USED

* Moving Average
* LSTM model

## LSTM ARCHITECTURE 
![lstm](https://i.ibb.co/0tBv9XL/Capture.jpg)
* We make use of two LSTM layers followed by a Dense layer.

## MOVING AVERAGE PERFORMANCE
* ![moving avg](https://i.ibb.co/6bn8n22/MOVING-AVG.jpg)
* From this we can see that the prediction using the moving average doesnt seem to work very well.

## LSTM MODEL PERFORMANCE
![LSTM](https://i.ibb.co/2sYM1ZB/lstm.jpg)
* From this we can see that our LSTM model makes accurate predictions on the stock price.
* Green is the actual price while Orange is the predicted price.
* The predicted and actual price are nearly the same.
