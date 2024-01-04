# Twitter Sentiment Analysis for Market Behavior Prediction

## Project Overview
This project aims to analyze tweets using various models to perform sentiment analysis. The sentiment analysis results are then used by a final estimator to predict market behavior.

## Data Source
The data used in this project is sourced from Kaggle.

## Methodology
1. **Data Collection**: Tweets are collected from a dataset available on [Kaggle](https://www.kaggle.com/datasets/kaushiksuresh147/bitcoin-tweets). 
2. **Sentiment Analysis**: Each tweet is analyzed using different models to determine its sentiment. The sentiment scores range from negative to positive, indicating the sentiment expressed in the tweet.
3. **Market Behavior Prediction**: The sentiment scores from the different models are input into a final estimator. This estimator predicts market behavior based on the sentiment analysis results.

## Models Used
- Model 1: [ProsusAI/finbert](https://huggingface.co/ProsusAI/finbert)
- Model 2: [mrm8488/distilroberta-finetuned-financial-news-sentiment-analysis](https://huggingface.co/mrm8488/distilroberta-finetuned-financial-news-sentiment-analysis)
- - Model 3: [lxyuan/distilbert-base-multilingual-cased-sentiments-student](https://huggingface.co/lxyuan/distilbert-base-multilingual-cased-sentiments-student)
- Final Estimator: XGBClassifier()

## Results
The final estimator is able to predict whether the market will move up or down with an accuracy of 70%.
