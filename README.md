# News-Virality-Prediction
This is an attempt to predict the number of shares a news article might get based on different factors, namely:
- The number of words in the title
- The number of words in the article
- Number of unique words
- Number of non stop words
- Number of non stop unique words
- Number of links in the article
- Number of images in the article
- Number of videos in the article
- Average length of the words
- Number of keywords in the article
- The article type/category (as in, entertainment, business etc)
- The day of the week when the article was posted
- Whether the day is a weekend or not
- Global subjectivity of the article
- Global sentiment polarity
- Global rate of the positive words
- Global rate of the negative words
- Average positive polarity
- Minimum positive polarity
- Maximum positive polarity
- Average negative polarity
- Minimum negative polarity
- Maximum negative polarity
- Title Subjectivity
- Title Sentiment Polarity

A dataset from UCI has been taken to train the model, it is available in https://archive.ics.uci.edu/ml/datasets/online+news+popularity. I have used Random Forest Regression to train this model.
