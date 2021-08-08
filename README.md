# Sentiment-Analysis

Analyse customer's sentiments based on their movie reviews in the IMDB database

DOMAIN: Digital content and entertainment industry

CONTEXT: The objective of this project is to build a text classification model that
analyses the customer's sentiments based on their reviews in the IMDB database. The
model uses a complex deep learning model to build an embedding layer followed by
a classification algorithm to analyse the sentiment of the customers.

DATA DESCRIPTION: The Dataset of 50,000 movie reviews is from IMDB, labelled by
sentiment (positive/negative). Reviews have been preprocessed, and each review is
encoded as a sequence of word indexes (integers). The words are
indexed by their frequency in the dataset, meaning the for that has index 1 is the
most frequent word. I have used the first 20 words from each review to speed up training,
using a max vocabulary size of 10,000.

PROJECT OBJECTIVE: I have build a LSTM NLP classifier which can use input text
parameters to determine the customer sentiments. Relevant sequence adding on the data is done followed by building a
sequential NLP Model using LSTM.

