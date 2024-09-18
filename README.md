# Fake News Detection
![logo](images/fnd.jpg)


## Introduction
Fake news is a serious problem in today's digital age, where information spreads rapidly through various online platforms. The circulation of fake news can have a significant negative impact on people and culture. This project utilizes machine learning algorithms to automatically determine the authenticity of news articles. The goal of the project is to develop a machine learning model that can identify any news article and classify it as fake or not. Three methods were used to determine the model's results.
- Random Forest Classifier
- Passive Aggressive Classifier
- SVM Classifier


## Dataset
The [FakeNewsNet dataset](https://github.com/KaiDMML/FakeNewsNet) contains news articles along with their corresponding labels (1 or 0).       
(1): True or Genuine news articles                                                                                                             
(0): Fake or fabricated news articles                                                                                                          
It is containing two datasets, Politifact  and Gossipcop , that are collected from two news fact-checking websites. In this project, we just use 'Gossipcop news' with a total of 19279 samples, 4190 "fake" and 15089 "real" articles.


## Approach
![flow chart](images/flowchart.png)

It is shown in the above graph that for this goal we use two kinds of features and implement the models on them separately, 1: tf-idf 2: content features(extracted from text)

## Results
The performance of each classifier was evaluated using metrics such as accuracy, precision, recall, and F1 score. As you see the dataset is imbalanced and it also affects the results.
