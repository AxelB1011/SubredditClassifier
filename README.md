# SubredditClassifier
Made using Huggingface API

Trained a distilbert-base-uncased model on a provided jsonfile which was a dictionary containing subreddits as keys and posts as values.

Training was done using a train-valid-test split.

Tested the model on a given jsonfile containing subreddits and posts. Removed the labels from dataset for prediction, used the labels to measure accuracy which was 0.9/90%.
