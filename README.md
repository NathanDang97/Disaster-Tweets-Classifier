# Disaster Tweets Classifier

## Overview

From the [Competition's Webpage](https://www.kaggle.com/competitions/nlp-getting-started/overview): Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster. Take the following tweet as an example: "On plus side TAKE A LOOK AT THE SKY LAST NIGHT IT WAS ABLAZE" (tweet source can be found [here](https://twitter.com/AnyOtherAnnaK/status/629195955506708480)). The author explicitly uses the word “ABLAZE” but means it metaphorically. This is clear to a human right away, especially with the visual aid. But it’s less clear to a machine.

In this competition, you’re challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. You’ll have access to a dataset of over 10,000 tweets that were hand classified (specifically, 7613 tweets for training, and 3263 tweets for testing).

**Disclaimer**: The dataset for this competition contains text that may be considered profane, vulgar, or offensive.

## Data Description

Below is the description of each attached data files in this project. The files can be found under the Data folder in this repository.

- train.csv - the training set containing 7613 tweets
- test.csv - the test set containing 3263 tweets

## Implementation

We implemented the DistilBERT by HuggingFace and a customized LSTM model and then compare the performance of both. The best accuracy score was 0.818. Full implementation with all steps (EDA, Feature Engineering, Model Devlopment, and Evaluation) can be found under the Main Folder in this repository.
