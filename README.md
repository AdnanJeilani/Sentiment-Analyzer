# Sentiment Analysis of Tweets

This project aims to perform sentiment analysis of tweets using Python and the TextBlob library.

## Prerequisites
Before you begin, ensure you have met the following requirements:

You have installed Python on your local machine.
You have installed the following libraries:
pandas
matplotlib
textblob
wordcloud
You have obtained a valid Twitter API key

To install the required libraries, use the following pip command in the terminal or command prompt:

Copy code
#### pip install pandas matplotlib textblob wordcloud

The code performs the following steps:

Loads the dataset containing tweets into a pandas dataframe.
Cleans the data to remove any unwanted characters or words.
Calculates the subjectivity and polarity of each tweet using the TextBlob library.
Adds the subjectivity and polarity values as columns in the dataframe.
Sorts the dataframe based on polarity and displays all positive and negative tweets.
Calculates the percentage of positive, negative, and neutral tweets.
Plots the polarity and subjectivity of each tweet in a scatter plot.
Plots the distribution of sentiments in a bar plot.
Generates a wordcloud of all the tweets to visualize the most frequent words.
Conclusion

This code provides a basic example of how to perform sentiment analysis of tweets using Python and the TextBlob library. You can further modify and improve the code as per your requirements.
