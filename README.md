# NLP Analysis on StockForum Money Control
# Author: Aneerudh Ravishankar

## Overview

This project aims to scrape data from the MoneyControl stock forum, to analyze the sentiment and frequency of discussions related to various stocks, and identify potential investment opportunities based on the above analysis.

## Table of Contents

- [Data Collection](#data-collection)
- [Sentiment Analysis](#sentiment-analysis)
- [Frequency Analysis](#frequency-analysis)
- [Stock Recommendations](#stock-recommendations)
- [Conclusion](#conclusion)
- [Disclaimer](#disclaimer)


## Data Collection

To collect data from the MoneyControl stock forum, we used web scraping techniques. The following steps were involved:
- Identify relevant forum threads and categories.
- Use web scraping libraries like `rvest` or `beautifulsoup` to extract discussions, timestamps, and user comments.
- Store the scraped data in a structured format for analysis.


## Sentiment Analysis

Sentiment analysis was performed on the collected data to determine the sentiment of discussions related to each stock. The sentiment analysis process involved:
- Using sentiment lexicons to classify text into positive, negative, or neutral sentiment.
- Calculating sentiment scores for each stock based on user comments.

## Frequency Analysis

Frequency analysis helps identify stocks that are frequently discussed on the forum. This can provide insights into the popularity and potential interest in specific stocks. The frequency analysis included:
- Counting the number of mentions for each stock in forum discussions.

## Stock Recommendations

Based on the sentiment and frequency analysis, the stock recommendations are displayed as dataframe or can be downloaded as a csv. These recommendations are not financial advice but are intended to highlight stocks that show positive sentiment and are frequently discussed. Investors should conduct further research before making investment decisions.

## Conclusion

This project demonstrates how to scrape data from the MoneyControl stock forum, perform sentiment and frequency analysis, and make stock recommendations. The results can serve as a starting point for further research and analysis in the field of stock market investment.

Feel free to explore the code and data in this repository to replicate the analysis or adapt it for your specific needs.

Happy analyzing!
  
## Disclaimer
- The information in this model is provided for educational purposes only and should not be considered as financial advice. Users should conduct independent research and consult with a qualified financial advisor before making any investment decisions. We do not guarantee the accuracy or reliability of the information, and its use is at the user's own risk.

