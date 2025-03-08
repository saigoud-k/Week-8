# Week-8



We install necessary libraries like textblob and vadersentiment to analyze sentiment.

# !pip install vadersentiment

# !pip install textblob

Loading Reddit Data

- We connect to an SQLite database (co_reddit.sqlite) and load posts into a Pandas DataFrame (df).
 Once the data is retrieved, we close the connection.

Keyword-Based Sentiment Analysis

- We load a sentiment dictionary (AFINN-en-165.txt), which contains words paired with sentiment scores.
- We store it as a Pandas DataFrame and then convert it into a dictionary (sentiment_dict) for quick lookups.

Processing Post Titles for Sentiment

- We likely apply our sentiment dictionary to analyze sentiment in post titles.
- We use NumPy and Pandas to process and score the data.

Visualizing Sentiment Scores

- histograms display the sentiment distribution.