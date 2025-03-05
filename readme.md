### SMS Spam Detection

# Author: [SaqlainMushtaq](https://github.com/Salahuddin-Aayubi)


Overview
This project aims to build a Spam Detection System for SMS messages using Natural Language Processing (NLP) and Machine Learning. The model classifies SMS messages as Spam or Ham (Legitimate) using a Naïve Bayes classifier trained on the SMS Spam Collection Dataset.

The implementation involves text preprocessing, feature extraction using TF-IDF, and classification using the Multinomial Naïve Bayes algorithm. The model is evaluated on real-world spam messages and provides accurate predictions.

Dataset Description
The dataset used is the SMS Spam Collection, which consists of 5,574 SMS messages labeled as:

Ham (Legitimate SMS)
Spam (Unwanted Promotional/Fraud Messages)
The dataset was collected from various public sources and is commonly used for research in spam detection.



Example Predictions

SMS Message  														Prediction
Congratulations! You've won a free lottery. Click here to claim.	spam
Hey, are we still meeting at 5 PM?									ham
Urgent! Click this link to claim your prize!						spam
