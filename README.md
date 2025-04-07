# Stock-News-Sentiment-Analysis 📰📈

**Analyzing Market Sentiment from News Headlines & Stock Price Impact**

A Python-based tool that performs sentiment analysis on financial news (earnings reports, headlines, press releases) and correlates it with stock price movements in real time. Designed for traders, researchers, and data enthusiasts to quantify how news sentiment influences markets.

## Key Features
- 🎯 **News Sentiment Scoring**: Uses NLP (VADER, BERT, or FinBERT) to classify sentiment from news text
- 📉 **Stock Data Integration**: Fetches historical/pricing data (Yahoo Finance)
- 📊 **Visualization**: Generates time-series plots (Plotly/Matplotlib) of sentiment vs. price
- ⚡ **Extensible**: Can plug into live news APIs (NewsAPI, Bloomberg) for real-time alerts

## Tech Stack
- `Python` | `Pandas` | `NLTK/spaCy` 
- `Hugging Face` (Transformers) 
- `Yahoo Finance API`/`Alpha Vantage`

## Installation
```bash
git clone https://github.com/JustAthar19/Stock-news-sentiment-analysis.git
pip install -r requirements.txt
