# NLP-Disaster-Tweets-Kaggle-Mini-Project


## Introduction
I’ll walk you through my mini-project NLP Disaster Tweets Kaggle Mini-Project, where I participated in the Kaggle competition "Natural Language Processing with Disaster Tweets." My goal was to classify tweets as either reporting a disaster or not.

Data Format: Each sample in the train and test sets contains:

The text of a tweet
A keyword from the tweet
The location the tweet was sent from
Task: Predict if a tweet is a disaster or not

File Details

train.csv: Contains the training set, including the target variable.
test.csv: Contains the test set.
sample_submission.csv: A sample file formatted for submissions.
Columns in the train dataset:

id: Unique identifier for each tweet
text: The tweet's content
location: The tweet's sending location (may be blank)
keyword: A keyword from the tweet (may be blank)
target: Indicates if the tweet is about a real disaster (1) or not (0) in train.csv only.