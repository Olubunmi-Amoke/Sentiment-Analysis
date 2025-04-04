# Sentiment-Analysis

## Problem Statement
**Business Context**

The prices of the stocks of companies listed under a global exchange are influenced by a variety of factors, with the company's financial performance, innovations and collaborations, and market sentiment being factors that play a significant role. News and media reports can rapidly affect investor perceptions and, consequently, stock prices in the highly competitive financial industry. With the sheer volume of news and opinions from a wide variety of sources, investors and financial analysts often struggle to stay updated and accurately interpret its impact on the market. As a result, investment firms need sophisticated tools to analyze market sentiment and integrate this information into their investment strategies.

**Problem Definition**

With an ever-rising number of news articles and opinions, an investment startup aims to leverage artificial intelligence to address the challenge of interpreting stock-related news and its impact on stock prices. They have collected historical daily news for a specific company listed under NASDAQ, along with data on its daily stock price and trade volumes.
The goal of this project is to analyze the data and develop an AI-driven sentiment analysis system that will automatically process and analyze news articles to gauge market sentiment, and summarize the news at a weekly level to enhance the accuracy of their stock price predictions and optimize investment strategies. This will empower the financial analysts with actionable insights, leading to more informed investment decisions and improved client outcomes.

#### Data Dictionary
- Date : The date the news was released
- News : The content of news articles that could potentially affect the company's stock price
- Open : The stock price (in $) at the beginning of the day
- High : The highest stock price (in $) reached during the day
- Low : The lowest stock price (in $) reached during the day
- Close : The adjusted stock price (in $) at the end of the day
- Volume : The number of shares traded during the day
- Label (1: positive, 0: neutral, -1: negative): The sentiment polarity of the news content

#### Conclusions and Recommendations
- **Insights from Visualizations:**

Line plots of Open, High, Low, and Close prices show daily fluctuations.
The dual-axis line plot illustrates the relationship between closing price and trading volume. Sudden spikes in volume often coincide with sharp price movements.
The countplot shows a higher frequency of neutral sentiments, which could indicate that most news articles are unbiased.

- **Business Recommendations:**

*Leverage Sentiment Trends for Market Predictions*: Use historical sentiment vs. price movement to develop early warning signals for trading decisions.

*Monitor Volume Spikes*: Large trading volumes following sentiment changes can help validate news-driven stock movements.
