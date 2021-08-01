# FIDELITY STOCK PRICE PREDICTION
![fidelity](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.investopedia.com%2Ffidelity-review-4587897&psig=AOvVaw0Tcn1Q3WvIETkOOF77leTm&ust=1627903894749000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCKibyt3cj_ICFQAAAAAdAAAAABAD)

## OVERVIEW
* In this project we try to predict the price of Fidelity National Financial Inc.
* In this project we make use of LSTM recurrent neural network to make time series forecasting.

## DATASET
* I downloaded this data from [yahoo_finance](https://in.finance.yahoo.com/)
* I downloaded the data since 1.08.2016
* You can access the data i used by downloading the file named FNF.csv 
* You can also download up to date data from [here.](https://in.finance.yahoo.com/quote/FNF/history?p=FNF)

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
* Auto ARIMA
* LSTM model

## LSTM ARCHITECTURE 
![lstm](https://i.ibb.co/0tBv9XL/Capture.jpg)
* We make use of two LSTM layers followed by a Dense layer.

## MODEL PERFORMANCE
![LSTM](https://i.ibb.co/hWBSqqS/Capture.jpg)
* From this we can see that our LSTM model makes accurate predictions on the stock price.
* Green is the actual price while Orange is the predicted price.
* The predicted and actual price are nearly the same.