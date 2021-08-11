# FIDELITY STOCK PRICE PREDICTION

## OVERVIEW
* In this project we predict the price of Fidelity National Financial Inc.
* In this project we make use of LSTM recurrent neural network to make time series forecasting.

## DATASET
* I downloaded this data from [yahoo_finance](https://in.finance.yahoo.com/quote/FNF/history?p=FNF).
* I downloaded the data since 2.08.2016.
* You can access the data i used by downloading the file named [Fidelity.csv](https://github.com/srikanth2102/CITIBANK_STOCK_PREDICTION/blob/main/Fidelity.csv).

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
![moving average](https://user-images.githubusercontent.com/66214509/128991034-70e476e8-1649-4e76-8e48-81ef05e0602d.JPG)

* From this we can see that the prediction using the moving average doesnt seem to work very well.

## LSTM MODEL PERFORMANCE
![lstm](https://user-images.githubusercontent.com/66214509/128991117-24198df0-95e6-4e09-b2c9-2427cdf1ecd3.JPG)

* From this we can see that our LSTM model makes accurate predictions on the stock price.
* Green is the predicted price while Orange is the actual price.
* The predicted and actual price are nearly the same.
