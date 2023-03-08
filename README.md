# Sentiment Analysis of Safaricom Tweets Using LSTM Model

## Overview

In this project, we will collect tweets using the Twitter API about Safaricom, a leading telecommunications company in Kenya. The objective is to perform sentiment analysis on these tweets to determine how customers perceive the company. We will use a machine learning model trained on the Sentiment 140 dataset, which contains 1.6 million tweets labelled as positive, negative, or neutral. After training the model, we will make predictions on the Safaricom tweets and visualize the results using various charts and graphs.

## Tools Used

We will use the following tools to accomplish our objectives:

- **Python**: a programming language for data analysis and machine learning
- **Twitter API**: to collect Safaricom tweets
- **Sentiment 140 dataset**: for training the machine learning model
- **Keras (LSTM model)**: for training and making predictions on the Safaricom tweets
- **NeatText**: a Python package for text cleaning
- **Matplotlib**: a data visualization library
- **Seaborn**: a data visualization library for statistical graphics
- **WordCloud**: a Python package for generating word clouds

## Steps

The project will involve the following steps:

1. **Collect Safaricom tweets using Twitter API**: We will use the Twitter API to collect tweets that contain the keyword "Safaricom".
2. **Clean the collected tweets using NeatText**: We will use NeatText to remove stop words, URLs, hashtags, and other irrelevant text from the collected tweets.
3. **Train the LSTM model using Sentiment 140 dataset**: We will train the LSTM model using the Sentiment 140 dataset, which contains 1.6 million tweets labelled as positive, negative, or neutral.
4. **Test the model using a validation set**: We will test the performance of the LSTM model using a validation set of Safaricom tweets that were manually labelled as positive, negative, or neutral.
5. **Make predictions on the collected Safaricom tweets**: We will use the trained LSTM model to make predictions on the Safaricom tweets that were collected in step 1.
6. **Visualize the results using Seaborn and WordCloud**: We will use Seaborn to create visualizations of the sentiment analysis results, such as bar charts and pie charts, and WordCloud to generate word clouds that show the most frequently used words in the Safaricom tweets.

## Expected Outcome

The expected outcome of this project is a sentiment analysis report on Safaricom tweets, which will show the overall sentiment towards the company as well as the most commonly used words in the tweets. The report will be presented in the form of charts, graphs, and word clouds, making it easy to interpret the findings.

## Conclusion

Sentiment analysis is a powerful tool for understanding how customers perceive a company or product. In this project, we have demonstrated how to use an LSTM model trained on the Sentiment 140 dataset to perform sentiment analysis on Safaricom tweets. By visualizing the results using Seaborn and WordCloud, we can gain insights into the most commonly used words and overall sentiment towards the company. This project can be extended to analyze tweets for other companies or products.

