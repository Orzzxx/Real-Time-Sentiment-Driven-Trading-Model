# Real-Time-Sentiment-Driven-Trading-Model
**Real-Time Sentiment-Driven Trading System :**
A Python-based tool that integrates real-time stock price data from Yahoo Finance and sentiment analysis from Reddit posts to generate automated trading signals. Utilizes machine learning (Random Forest Classifier) to predict price movements and provides visualizations of trading strategies.

**Features :**
Fetches minute-by-minute stock data using yfinance.
Analyzes sentiment from Reddit posts in subreddits like stocks, investing, and wallstreetbets using NLTK’s VADER model.
Trains a Random Forest Classifier to predict stock price direction.
Generates buy/sell signals based on sentiment trends, price moving averages, and ML predictions.
Visualizes price trends, sentiment scores, and trading signals with Matplotlib.
Operates in real-time with customizable update intervals (default: 5 minutes) in Indian Standard Time (IST).
**Prerequisites :**
Python 3.11+
Required libraries: yfinance, pandas, numpy, matplotlib, nltk, praw, scikit-learn
Reddit API credentials (client ID, client secret, user agent)
