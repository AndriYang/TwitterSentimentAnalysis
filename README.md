# TwitterSentimentAnalysis

This repository contains a project based on Twitter Sentiment Analysis for Hateful speech that was done during the Computational Data Science Course - 50.038, that we attended at SUTD. 

## TwitterCrawlingScript
Our means of getting our dataset
- Uses Twitter API
- Use python libraries like numpy, pandas, and tweepy

## Basic_data_cleaning_functions
A notebook meant for easing up data pre-processing
- Uses libraries like numpy, pandas and nltk
- Contains very basic helper functions for cleaning up data (eg lowercasing, hashtag removal)
- Has functions for removing duplicates or rebalancing your dataset (binary only for now)

## TwitterSentimentAnalysis
The main part of our code where we tested out various traditional models for Sentiment Analysis
- Models used include (from keras): SimpleRNN, LSTM, Bidirectional LSTM
- We tested out CUDA's implementation of LSTM and Bidirectional LSTM as well: CuDNNLSTM, Bidirectional CuDNNLSTM
- Used Earlystopping, Dropout and K cross validation to find more meaningful observations and to help improve performance
