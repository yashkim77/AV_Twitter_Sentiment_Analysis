#  Twitter Sentiment Analysis

## About Twitter Sentiment Analysis

Sentiment Analysis refers to the use of natural language processing, text analysis, computational linguistics, and biometrics to systematically identify, extract, quantify, and study affective states and subjective information. Sentiment analysis is widely applied to voice of the customer materials such as reviews and survey responses, online and social media, and healthcare materials for applications that range from marketing to customer service to clinical medicine.



## Problem Statement

The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.

Formally, given a training sample of tweets and labels, where label '1' denotes the tweet is racist/sexist and label '0' denotes the tweet is not racist/sexist, your objective is to predict the labels on the test dataset.

## Data
Our overall collection of tweets was split in the ratio of 65:35 into training and testing data. Out of the testing data, 30% is public and the rest is private
* **train.csv - For training the models, we provide a labelled dataset of 31,962 tweets. The dataset is provided in the form of a csv file with each line storing a tweet id, its label and the tweet.**
* **test_tweets.csv - The test data file contains only tweet ids and the tweet text with each tweet in a new line.**

### Evaluation Metric

The metric used for evaluating the performance of classification model would be F1-Score.

 

The metric can be understood as -

 

True Positives (TP) - These are the correctly predicted positive values which means that the value of actual class is yes and the value of predicted class is also yes.

True Negatives (TN) - These are the correctly predicted negative values which means that the value of actual class is no and value of predicted class is also no.

False Positives (FP) – When actual class is no and predicted class is yes.

False Negatives (FN) – When actual class is yes but predicted class in no.

Precision = TP/TP+FP

Recall = TP/TP+FN

 

F1 Score = 2*(Recall * Precision) / (Recall + Precision)

 

F1 is usually more useful than accuracy, especially if for an uneven class distribution.
 

### Leaderboard 
* **[Public LB](https://datahack.analyticsvidhya.com/contest/practice-problem-twitter-sentiment-analysis/lb** : **10th/645 Rank**


