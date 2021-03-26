Member :  
1. Matthew Brian Darmadi
2. Aidan Bossio
3. Dante Monaldo

Summary: We used an SPY dataset from Alpha Vantage. SPY is an index fund that tracks the S&P 500 index. Our goal was to find a model that would accurately predict the closing price of SPY. The preprocessing of the data was creating a new data frame that would allow us to test the next day’s closing price based on the current day’s data (opening price, closing price, highest price, lowest price, trade volume).A lot of the work for DAP5 was applicable to DAP6. Determining the closing price of SPY is a regression problem because it requires predicting a continuous value. Models that we tested were regression with tanh, relu, and logistic functions which are part of the Python Neural Network library. By analyzing R-squared, RMSE and the K-cross validation scores, we determined that artificial neural networks have a 98% accuracy for predicting the closing price. This was calculated with an 80/20 train-test split.
