# Bsc.Project

## Introduction
Sentiment analysis is a natural language processing (NLP) task that involves using machine learning and deep learning models to analyze sentiments, opinions, and attitudes in textual data. In this project, we focus on sentiment analysis of tweets from users, categorizing them into positive, negative, or neutral sentiments. We use various machine learning and deep learning models to achieve this task.

## Project Overview
The project can be divided into the following main steps:

1. Data Preprocessing: Preprocessing the training dataset to remove unnecessary parts of the tweets and perform tokenization. Links, mentions, numbers, and hashtags are handled appropriately.
2. Word Embedding with Word2Vec: Using Word2Vec to create word embeddings for the tweet words to prepare them for the neural network models.
3. Model Training: Training the neural network models on the preprocessed and embedded data using different architectures.
    - Convolutional Neural Network (CNN): A CNN model with ReLU activation and zero padding for out-of-vocabulary words is trained.
    - Long Short-Term Memory (LSTM) Network: An LSTM model is used with embedding layers for sequence processing.
    - Feedforward Neural Network (FNN): A simple fully connected neural network is trained for sentiment classification.
4. Model Evaluation: Evaluating the trained models using performance metrics such as accuracy, precision, recall, and F1 score.
5. User Interface with Flask: Implementing a simple user interface using Flask to interact with the sentiment analysis system. Users can input tweets, and the system will display the sentiment prediction from different neural network models.


## Results
After evaluating the models, the selected model for sentiment analysis is the first type of Convolutional Neural Network (CNN) with ReLU activation and zero padding. It achieved an accuracy of 76% and a weighted F1 score of 73% on the test dataset, outperforming the other models.

## Conclusion
The sentiment analysis system developed in this project provides a user-friendly interface for predicting the sentiment of input tweets using different neural network models. The selected CNN model with appropriate preprocessing and embedding methods demonstrates satisfactory performance and serves as a valuable tool for analyzing users' sentiments on vaccination.


