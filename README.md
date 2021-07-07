# Stock-Prediction-Using-Twitter-Sentiment-Analysis
An overview of the process flow of my project is as follows:

Data Collection & Parsing: The stock market data is collected using yfinance API and tweets are fetched from twitter using GetOldTweets API. In this step the preprocessing of the tweets such as removing stop words, hyperlink and other steps are carried out.
Sentiment Analysis: The sentiment analysis of the tweet is carried out using VADER. Here each tweet is given a sentiment score which determines if the tweet is positive, negative or neutral.
Processing: The rows which have missing values such as price values are further processed. The data along with the sentiment scores is divided into train and test data and is fed to the model.
Applying Regression Models: To predict stock Market prices, we have used Random Forest and Support vector regression models in this project.RMSE scores to validate the efficiency of model and to analyze which model works better for the used dataset.
