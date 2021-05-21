NLP - Tales from the Crypto

## Background

There's been a lot of hype in the news lately about cryptocurrency, so you want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.

This project aims to apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum and to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

### Files

[Crypto Sentiment Notebook](Code/crypto_sentiment.ipynb)

### Sentiment Analysis:

Used the [newsapi](https://newsapi.org/) to pull the latest news articles for Bitcoin and Ethereum and created a DataFrame of sentiment scores for each coin.

- Q: Which coin had the highest mean positive score?
    A: BTC (0.072) had the highest vs ETH (0.051)
- Q: Which coin had the highest compound score?
    A: BTC (0.921) had the highest vs ETH (0.709) 
- Q. Which coin had the highest positive score?

    A: BTC (0.353) had the highest vs ETH (0.144)

#### Natural Language Processing

1. Use NLTK and Python to tokenize the text for each coin.
2. Look at the ngrams and word frequency for each coin.
3. Use NLTK to produce the ngrams for N = 2.
4. List the top 10 words for each coin.
5. Generate word clouds for each coin to summarize the news for each coin.

