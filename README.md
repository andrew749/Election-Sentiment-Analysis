# Election Sentiment Analysis

## A quick notebook I toyed around with the night of the 2016 presidential election.


I train a classifier on a set of movie reviews to try to create
a model for sentiment. Reviews are tokenized using TFIDF and then the
respective TFIDF scores are used to train an SVM classifier. This classifer now
knows a very basic understanding of what words correspond to positive and
negative emotions/events. From here, incoming tweets are tokenized and the
generated model is used to predict the sentiment of the tweet.
