# Twitter Sentiment Analysis on Palestine Tweets

This project performs sentiment analysis on tweets related to Palestine using PySpark, TextBlob, and Nitter scraper. The analysis includes extracting tweet data, performing sentiment categorization, and building a Naive Bayes classification model.

## Features

* **Tweet Scraping:** Collect tweets using Nitter scraper.
* **Sentiment Analysis:** Use TextBlob to compute sentiment scores and categorize them as 'Happy', 'Sad', or 'Neutral'.
* **Visualization:** Generate sentiment distributions and word clouds for positive sentiment tweets.
* **Naive Bayes Classifier:** Build a machine learning model to classify tweets based on the number of likes.
* **Cross-validation:** Perform cross-validation to improve model accuracy.
* **Streamlit App:** Deploy a web interface to predict sentiment for a user-provided tweet.

## Installation

1. Install the necessary dependencies:
   ```bash
   pip install ntscraper
   pip install textblob
   pip install pyspark
   pip install streamlit
   pip install wordcloud
