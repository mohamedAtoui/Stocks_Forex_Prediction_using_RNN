-The next code do a prediction for the next day closing price using RNN:

-the model was trained to predict one day closing price based on the last 60 days and so on.

-I used RMSE to measure accuracy, which was in my case  0.007£, but what does it mean?
  it means the the mean value error is (+/-)0.007£ pound which is fine enough because forex market has lower percentage changes a day logically the error will be low as well.

-The code give at the end the prediciton for the next day closing price.


Libraries used: matplotlib, pandas, numpy, sklearn, tensorflow, yfinance

