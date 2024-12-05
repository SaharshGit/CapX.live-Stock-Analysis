# Automotive Stock Prediction Using Reddit Data

This project predicts stock price movements for companies in the automotive sector using sentiment analysis on Reddit posts and comments. The process involves scraping Reddit data, analyzing sentiment, and merging it with stock price data to create a predictive model.
## Features

- **Data Scraping**: Collects data from multiple automotive-related subreddits.
- **Sentiment Analysis**: Uses sentiment analysis to classify Reddit posts and comments as positive, negative, or neutral.
- **Stock Data Integration**: Fetches historical stock data using the Yahoo Finance API.
- **Prediction Model**: Uses machine learning models (e.g., Random Forest, XGBoost) to predict stock price movement.
- **Evaluation Metrics**: Evaluates the model performance using accuracy, precision, recall, and F1-score.

## Requirements

This project requires Python 3.x and the following dependencies:

- `pandas`
- `numpy`
- `matplotlib`
- `yfinance`
- `praw`
- `vaderSentiment`
- `scikit-learn`
- `xgboost`
- `seaborn`

## How to run the code
- We have 3 Notebooks 'Reddit_Scraping.ipynb', 'Analysis and Feature creation.ipynb' and 'Prediction_Model.ipynb'. You should run the notebooks in same order.
- 'Reddit_Scraping.ipynb' will output 'scrapped_data.csv' file. This file will be required in 'Analysis and Feature creation.ipynb' notebook.
- 'Analysis and Feature creation.ipynb' will output 'final_reddit_data.csv'. This file will be required in 'Prediction_Model.ipynb' notebook.
  
- I would recommed running them in google collab for similar results 

## Short description of each Notebook
- 'Reddit_Scraping.ipynb' - Scrapes reddit data, historical data and combine them based on date and company name.
- 'Analysis and Feature creation.ipynb' - Performs sentiment analysis and creates new features.
- 'Prediction_Model.ipynb' - train and test different ML models on 'final_reddit_data.csv' dataset.

