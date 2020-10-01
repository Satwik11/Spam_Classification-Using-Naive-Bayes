# Spam_Classification-Using-Naive-Bayes

Naive Bayes is a supervised classification technique based on Bayes' Theorem with an assumption of independence among predictors. That is, a Naive Bayes classifier assumes that the presence of a particular feature in a class is unrelated to the presence of any other feature.

It is a popular technique for text categorization, judging documents as belonging to one category or the other (such as spam or legitimate, sports or politics, etc.) with word frequencies as features.
![Test Image 1](https://miro.medium.com/max/1050/1*nBgCTU_hAVG00eYkcRf6Mw.png)

**Goal**: Previously unseen records should be assigned a class as accurately as possible

* We have a bunch of emails classified as 'spam' and a bunch of emails classified as 'ham' (not spam)
* The emails are first read and stored in a dataframe. They are then parsed using CountVectorize
* This information is used to train the model and its prediction is then tested with a sample input

**Python Libraries used**: pandas, numpy, io, os, CountVectorizer and MultinomialNB from sklearn

#### Some Practical Applications:
* Direct Marketing
* Fraud Detection
* Text Classification
* Spam Filtering
* Categorizing News
* Medical Diagnosis
* Face Recognition

## How to execute file:
The code files are in running condition and are directly executable
* Install all necessary libraries from Anaconda
