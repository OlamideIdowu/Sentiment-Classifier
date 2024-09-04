# Sentiment-Classifier
This repository contains a sentiment analysis model that predicts the sentiment of tweets. It leverages a *Naive Bayes* classifier trained on tweet data and uses *TF-IDF* for feature extraction.
- *naive_bayes_model.pkl*: Pre-trained Naive Bayes model for sentiment classification.
- *tfidf_vectorizer.pkl*: Pre-fitted TF-IDF vectorizer used to transform tweets into feature vectors.
- *Tweets.csv*: A dataset of tweets that can be used for prediction and evaluation.

pandas==1.5.3
joblib==1.3.0
scikit-learn==1.2.2
numpy==1.24.3
