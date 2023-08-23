# Neural_Network_SP500_Leveraged_ETFs_Prices

This repository demonstrates leveraging a neural network to simulate S&P 500 ETF prices. In the absence of historical data for 2x SSO and 3x UPRO ETFs before 2006 and 2009 respectively, a neural network approximates daily leverage based on known S&P 500 daily percentage changes. Each neural network for SSO and UPRO employs an input layer, 2 hidden layers, and 1 output layer. Though code is generalized for multiple neurons per hidden layer. Median squared error validates the neural network with a pseudo early stopping approach, optimizing weight matrices for precise leverage price prediction. The code effectively reproduces SSO 2x ETF prices and closely approximates UPRO 3x ETF prices until around 2020. An insight into the neural network's limitations arises from UPRO's trading data starting later than SSO's, influencing price prediction accuracy. Enhancing the neural network's performance for UPRO entails accumulating more trading days' data for better predictions. Plots comparing predicted and median leveraged ETF prices highlight these dynamics.





