# Text-Classification
Sentiment Analysis on IMDB reviews and twitter data

## Implementation details

Performed sentiment analysis on IMDB movie reviews and Twitter data by classifying tweets/movie reviews as "positive" or "negative". A labeled training dataset consisting of 25000 movie reviews and 750000 tweets were used to build Logistic Regression and Naive Bayes classifier models. The test data set consisted of 25000 movie reviews and 150000 tweets.

Two approaches were considered for converting text data into feature vectors, a Bag of Words model utilizing only "important" words and a Doc2Vec model where document vectors were learned via artificial neural networks. The Doc2Vec feature generation was done using the gensim Python package.

Obtained a classification accuracy of ~80% for the movie reviews and ~60% for the twitter data
