# Stock-Predicting-Bot
## Summary
This bot will try to predict which stocks might 10x in 10 years. It will be using neural networks to analyze historical data from the past 10 years. It will train with stocks from the Nasdaq100 from 10 years ago. It will train with data from 2010, 2011 and 2012.
## Model explination
Neural network was used because it can easily recognize patterns that humans cannot and works well with non-linear and complex data like stock market data. Features inculded the most used indicators used by value investors such as P/B, P/S, P/E, Market cap and beta. Y will be 1 if a stock 10x anywhere from 2012 to 2022 and will be 0 if it does not. 75% of our data will be used for training and 25% will be used for testing
## Result
The model predicted stocks that would 10x correctly 18.75% of the time. But if it predicted that every stock would 10x, it wouyld be correct 11/63 (17.46%) of the time. With this comparison, it is safe to say that this bot is not very useful. This is probably because we did not have a large enough number of stocks in our data to work with (a lot of stocks were dropped due to missing data). Increasing the number of epochs did not help improve the accuracy.
## Possible future work
To improve the model, suggestions include:<br>
Increasing the number of hidden layers.<br>
Changing the activation function, such as from relu to swish.<br>
Changing the activation function in the output layer, such as from sigmoid to logistic.<br>
increasing the number of neurons.<br>
Adding more features like Graham fair value, forward P/E, free cash flow yield, entreprise value, 5 year return and 10 year return.<br>
Adding more stocks, such as from the S&P500 index.<br>
Changing the learning algorithm parameters, such as the percentage of test vs training data.<br>
Using oversampling to duplicate examples from the minority class.
