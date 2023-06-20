# IMDB-sentiment-classifier
In this data challenge you will analyze a subset of the Large Movie Review Dataset. The dataset consists of information from 50.000 reviews. For 14.911 of these reviews (training set), you know whether the sentiment was positive (response = 2) or negative (response = 1).

The input variable is the review itself. For the other 35.089 reviews (test set), you only have access to the text of the review but not the response.

Your goal is to construct a classifier that does well in labeling the response of the remaining 35089 reviews.

This data challenge is courtesy of [Bocconi Data Science Challenges](https://data-science-challenges.unibocconi.it/) and can be accessed [here](https://data-science-challenges.unibocconi.it/competitions/6f289091-feb6-417d-82c3-9c144e01b550).

## Model Evaluation
The formula measures the overall cost that you pay in miss-classifying the sentiment of the review. The specific costs can be found in the file weights-matrix.csv.
