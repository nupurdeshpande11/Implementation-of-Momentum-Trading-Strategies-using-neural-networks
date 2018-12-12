# Implementation-of-Momentum-Trading-Strategies-using-neural-networks
## Project is spit into 3 parts: 
## Part A is trying to oredict stock prices using neural nets(LSTM and GRU) without any strategy
## Part B is using simpke moving averages strategy with feature extraction amd external ticks
## Part C is using moving averages strategy without extrernal ticks and also implementing volatility testing
## Backtesting is performed for Part C stratergy for final closing price
## Data is in zip file for Part A.(there is code in Jupyter notebook to unzip the file)
## Data in .csv files are used for Part B and Part C. They are sampled from Part A, Users are encouraged to resamaple the OHLCV data from zip file into that in .csv file so they learn using different datasets
## All data is in OHLCV format and is historic stock prices of NASDAQ acquired from NASDAQ historical prices from Yahoo api,
## Utils and Feature.py have to be run with Volatility trading notebook. Same for backtesting.py with Backteasting notebook 
## Running: Run on Keras with Tensorflow backend. Highly encourage you to run AWS Deep Learning Ubuntu AMI EC2 instance
## Larger epochs may take time to train. Patience is necessary. 
## Final output strategies see accuracy of 40 to 50 % consistent with other research work on the subject.
## Refer to Startegy 2 and 3 for final momentum strategies
## Read explanation given in every Jupyter notebook
## Incase github doesn't load notebooks paste url in https://nbviewer.jupyter.org/
##
