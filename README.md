# Sentiment Analysis of Tweets

This project aims to perform sentiment analysis of tweets using Python and the TextBlob library.

### Prerequisites

Make sure you have the following libraries installed in your Python environment:

- wordcloud
- textblob
- matplotlib
- plotly
- pandas
- numpy
- tweepy
- nltk

You can install these libraries using pip:

```
pip install wordcloud textblob matplotlib plotly pandas numpy tweepy nltk
```
## Usage

1. Clone the repository to your local machine or download the code files.

2. Open the `Sentiment Analysis.ipynb` notebook in Jupyter or any compatible Python IDE.

3. Run the notebook to perform sentiment analysis on tweets. The code will access the Twitter API, retrieve tweets with the search term "spx," clean the text, calculate sentiment polarity and subjectivity, and analyze the sentiment of the tweets.

4. The results will be displayed through various visualizations, including a word cloud, scatter plot of polarity and subjectivity, and a bar chart of sentiment analysis counts.

## How It Works

1. Twitter API Authentication: The code reads Twitter API credentials from a CSV file and uses them to authenticate with the Twitter API.

2. Tweet Retrieval: Using the authenticated API object, the code searches for tweets containing the search term "spx." It retrieves up to 100 tweets in English since November 1, 2021.

3. Text Cleaning: The code defines a function to clean the tweet text by removing mentions, hyperlinks, and retweets using regular expressions. It applies this function to all the tweets in the DataFrame.

4. Sentiment Analysis: The code defines functions to calculate the subjectivity and polarity scores of each tweet using TextBlob. It applies these functions to the tweet text column in the DataFrame and stores the results in new columns.

5. Sentiment Classification: The code defines a function to classify the sentiment based on the polarity score. It adds an "Analysis" column to the DataFrame, which contains the sentiment category (positive, negative, or neutral) for each tweet.

6. Visualization: The code uses various libraries such as wordcloud, matplotlib, and plotly.express to visualize the sentiment analysis results. It creates a word cloud, scatter plot, and bar chart to provide insights into the sentiment of the tweets.

Note: The code assumes that you have a CSV file named "credentials.csv" containing the necessary Twitter API credentials. You should replace the placeholder values in the CSV file with your actual credentials.
