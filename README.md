# NLP-TwitterData

## Project Overview

In this capstone project, I will explore the basics of the Natural Language Processing (NLP) and demonstrate how to implement a pipeline that combines a traditional unsupervised learning algorithm with a deep learning algorithm to train an unlabeled large text data. Hence, the main objective is going to be to demonstrate how to set up that pipeline that facilitates collection and creation of raw text data, preprocessing and categorizing unlabeled text data to finally training and evaluating deep learning models in Keras.

Throughout this project, the following skills will be practiced:
 
* How to collect data from Twitter via Twitter API and Tweepy Python package
* How to efficiently read and clean up large text dataset with pandas
* How to preprocess text data using basic NLP techniques and generate features
* How to categorize unlabeled text data
* How to train, compile, fit and evaluate deep learning models in Keras


## Problem Statement
What are the main opinions observed from the tweets related to the 2020 US election? What are people talking about on Twitter two weeks prior to election day?

## Context
October surprise, according to Wikipedia, is a U.S. political jargon and a news event that may influence the outcome of an upcoming November election, particularly one for the U.S. presidency), whether deliberately planned or spontaneously occurring. Tweeter is a great source of unfiltered conversations, opinions and news events directly posted by the individuals themselves compared to the filtered news provided by the media outlets. This project analyses various sentiments from the tweets occurring 2 weeks prior to the election day to identify main topics people are talking about and October surprises. 

## Criteria For Success
Achieve at least 75% accuracy in predicting the topics of the tweets.

## Scope of Solution Space
Solution scope will be limited to analysing the tweets related to the 2020 US election. In the modeling section, the main focus will be given to the training and evaluating deep learning models with the text data. While labeling of the tweets is required as part of the project, it is out of the scope of the project to improve the performance of the labeling job. 

## Solution Approach

1. Collect data from the Twitter with the relevant keywords
2. Apply Natural Language Processing (NLP) techniques to clean and preprocess the data
3. Distributed computing will be used to preprocess and label the data set
4. Train and evaluate SimpleRNN and LSTM models in Keras

## Constraints

* Limitation of computational power/resource
* Limited hands-on experience in advanced deep learning techniques
* Access to the distributed computing platforms and technical challenges

## Stakeholders
General public

## Deliverables

* Final Report
* Final Presentation
* Jupyter notebooks with the code for each stage of the data science method
* Model deployment into production
* Article on Medium / TDS

## Data Sources
At the time of doing this project, the US 2020 election was just around the corner and it made sense to do sentiment analysis of tweets related to the upcoming election to learn about the kind of opinions and topics being discussed in Twitter just about 2 weeks prior to the election day. Twitter is a great source for unfiltered opinions as opposed to the typical filtered news we see from the major media outlets. As such, I will create my own dataset by collecting tweets from Twitter using the Twitter API and the python package Tweepy.
