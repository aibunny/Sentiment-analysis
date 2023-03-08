# Sentiment Analysis of Safaricom Tweets Using LSTM Model

## Overview

In this project, I collected tweets using the Twitter API about Safaricom, a leading telecommunications company in Kenya. The objective was to perform sentiment analysis on these tweets to determine how customers perceive the company. I used a machine learning model trained on the Sentiment 140 dataset, which contains 1.6 million tweets labelled as positive, negative, or neutral. After training the model, I made predictions on the Safaricom tweets and visualized the results using various charts and graphs.

## Tools Used

I used the following tools to accomplish my objectives:

- **Python**: a programming language for data analysis and machine learning
- **Twitter API**: to collect Safaricom tweets
- **Sentiment 140 dataset**: for training the machine learning model
- **TensorFlow (Keras, LSTM model)**: for training and making predictions on the Safaricom tweets
- **NeatText**: a Python package for text cleaning
- **Matplotlib**: a data visualization library
- **Seaborn**: a data visualization library for statistical graphics
- **WordCloud**: a Python package for generating word clouds

## Steps

The project involved the following steps:

1. **Collect Safaricom tweets using Twitter API**: I used the Twitter API to collect tweets that contain the keyword "Safaricom".
2. **Clean the collected tweets using NeatText**: I used NeatText to remove stop words, URLs, hashtags, and other irrelevant text from the collected tweets.
3. **Train the LSTM model using Sentiment 140 dataset**: I trained the LSTM model using the Sentiment 140 dataset, which contains 1.6 million tweets labelled as positive, negative, or neutral.
4. **Test the model using a validation set**: I tested the performance of the LSTM model using a validation set of Safaricom tweets that were manually labelled as positive or neutral.
    ![MODELS ACCURACY](image_file_path)

6. **Make predictions on the collected Safaricom tweets**: I used the trained LSTM model to make predictions on the Safaricom tweets that were collected in step 1.
7. **Visualize the results using Seaborn and WordCloud**: I used Seaborn to create visualizations of the sentiment analysis results, such as bar charts and pie charts, and WordCloud to generate word clouds that show the most frequently used words in the Safaricom tweets.

## Expected Outcome

The expected outcome of this project is a sentiment analysis report on Safaricom tweets, which will show the overall sentiment towards the company as well as the most commonly used words in the tweets. The report will be presented in the form of charts, graphs, and word clouds, making it easy to interpret the findings.

## Conclusion

Sentiment analysis is a powerful tool for understanding how customers perceive a company or product. In this project, I have demonstrated how to use an LSTM model trained on the Sentiment 140 dataset using TensorFlow to perform sentiment analysis on Safaricom tweets. By visualizing the results using Seaborn and WordCloud, I can gain insights into the most commonly used words and overall sentiment towards the company. This project can be extended to analyze tweets for other companies or products.

## Visualizations

Seaborn and WordCloud visualizations 
![PIE CHART](image_file_path)
![WORDCLOUD](image_file_path)


