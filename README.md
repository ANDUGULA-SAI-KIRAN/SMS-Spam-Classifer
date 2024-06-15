# SMS Spam Classifier
This project aims to develop a machine-learning model to detect spam messages in SMS text data. It utilizes natural language processing (NLP) techniques and a supervised learning algorithm to classify SMS messages as either spam or non-spam (ham).

## Dataset
The dataset used for this project is the "SMS Spam Collection" from the UCI Machine Learning Repository. It contains a collection of 5,574 SMS messages, labeled as spam or ham. 
**The dataset contains two columns:**
label: Indicates whether the message is spam (1) or ham (0).
text: The actual text content of the SMS message.

## Problem Statement: 
In today's technologically advanced world, there is a high likelihood of fraudulent transactions and the dissemination of fraudulent information. One such instance is SMS spam detection. The objective is to develop a machine learning model capable of predicting whether an SMS is spam or not-spam (ham), thereby enhancing the user experience and mitigating the risk of falling victim to spam-related scams.

**Interpreting model preformance by Term frequency-inverse document frquency & vectorization method**
![image](https://github.com/ANDUGULA-SAI-KIRAN/SMS-Spam-Classifer/assets/143734802/826d7cfd-7d1b-4775-9c17-616558fc0b4b)

Insights found from performance table-
first logistic regression alogorithm has highest accuracy 0.978 and precision 1 with Count vectorization method
second multinomial naive bayes algorithm has accuracy 0.973 and precision 1 with TF-IDF vectorization method
Evaluation metrics as accuracy and precision

**Accuracy - ** it measures overall correctness of the model, ratio of correctly classified instances to total number of instances in dataset
**Precision -** It measures propotion of coorectly identified spam messages among all messages predicted, ratio of correctly classified spam message to sum of correctly classified spam message and incorrectly classified spam message

**Note- Our model should correctly identify spam messages hence, precision should be 1**


