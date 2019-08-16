# Classifying-Malicious-and-Benign-Websites

### Introduction
We are going to analyze the Malicious and Benign websites Dataset, which is a research production of a team of PHD students in University of ICESI. This project attempts to analyze and visualize characteristics of malicious and benign websites.

> I'm analysing purely for learning purposes, so there may be notes regarding different topics that helps me remember what I learnt.

### Context
The project is created with the intention to evaluate how different classification models perform when predicting malicious and benign websites, based on application layer and network characteristics. The data were obtained by using different verified sources of benign and malicious URL's, in a low interactive client honeypot to isolate network traffic. We used additional tools to get other information, such as, server country with Whois.

### Results

#### Logistic Regression
> Accuracy: 0.933
  Precision: 0.539
  Recall: 0.636
  AUC: 0.806
  F1 Score: 0.700

#### Gaussian Naive Bayes
> Accuracy: 0.883
  Precision: 0.443
  Recall: 0.818
  AUC: 0.855
  F1 Score: 0.632

#### K-Nearest Neighbor
> Accuracy: 0.922
  Precision: 0.504
  Recall: 0.682
  AUC: 0.819
  F1 Score: 0.682

#### Decision Trees
> Accuracy: 1.000
  Precision: 1.000
  Recall: 1.000
  AUC: 1.000
  F1 Score: 1.000

#### SVM:
> Accuracy: 0.961
  Precision: 0.718
  Recall: 0.727
  AUC: 0.860
  F1 Score: 0.821

#### Source
The original dataset is located at: https://www.kaggle.com/xwolf12/malicious-and-benign-websites