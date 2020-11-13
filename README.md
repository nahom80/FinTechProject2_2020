# DigiSentiments

Jaimes,Bookers and Mohans Project - Team2Project2 - Columbia Fintech

The goal of this project was to develop a tool that can predict volatitlity for cryptocurrencies by:

-Analyzing publications for sentiment analysis.
-Use Machine Learning to make a prediction.

Our Approach

-Track down historical crypto data.
-Research crypto news outlets and Social Media.
-Use network specific meta as additional features for predictions( retweets / reddit comments )


Results of our project.

-There is a need for sophisticated data collection scripts to hunt down and scrape data for large scope projects.
-Using sentiment as a secondary feature seems  appropriate for stocks\securities.
-There isn’t enough historical data available on cryptocurrency compared to stocks and/or securities. 


Model 1 / Training
LSTM Keras Sequential Model
30 Day Volatility as target.
Number of Units 20
Epochs 40
Batchsize 20

Model 2 / Training
LSTM Keras Sequential Model
30 Day Rolling Volatility as target
Window Size 30
3 Feature Columns
5 Input Layers
300 epochs
Batchsize 30

Model 3 / Training
LSTM Keras Sequential Model
30 Day Rolling Volatility as target
Window Size = 1
3 Feature Columns
5 Input Layers
100 epochs
Batchsize 30

Model 4 / Training
LSTM Keras Sequential Model
30 Day Rolling Volatility as target
Window Size = 15
3 Feature Columns
6 Input Layers
150 epochs
Batchsize 15



