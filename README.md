# Twitter Sentiment Analysis

This project performs sentiment analysis on Twitter data, exploring entity-specific sentiments and creating visual insights. The dataset used in this project is processed for analysis, with various visualization techniques employed to understand the underlying trends.

## Features
- **Data Cleaning**: Removal of missing and duplicate entries to ensure dataset integrity.
- **Sentiment Analysis**: Analysis of tweets to identify positive, negative, or neutral sentiments.
- **Entity Analysis**: Exploration of entities mentioned in tweets and their sentiment distribution.
- **Data Visualization**:
  - Sentiment distribution plots.
  - Entity distribution plots.
  - Word cloud representation of tweet content.
  - Length distribution of tweets.
  - Entity-specific sentiment comparison.

## Dataset
The dataset used is `twitter_training.csv, which contains:
- `Id`: Unique identifier for each tweet.
- `Entity`: The entity mentioned in the tweet.
- `Sentiment`: The sentiment expressed (`Positive`, `Negative`, etc.).
- `Tweet`: The actual text of the tweet.
- Dataset:https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis

## Prerequisites
- Python 3.x
- Libraries:
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `wordcloud`

## Future Enhancements
- Integrate advanced NLP techniques for sentiment analysis.
- Develop a web application for real-time sentiment tracking.
