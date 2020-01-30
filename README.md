# Reddit Classifier

## Problem Statement

As the world gains access to internet, forum moderators faced difficulty in handling large amount of spams or misclassified post.

In this project, we aim to perform research,building and implementation of a NLP classifier model. The model which we have created is a binary classification model. This will be a proof-of-concept for the management of online forums. Upon successful POC, this project could be further taken into a scalable project for multi-class classification with sound budget.

## Executive Summary

As the world becomes more developed, human beings have realised the importance of overall well being both mentally and physically. Understanding text through Natural Language Processing techniques of two subreddit Mental Health and Fitness gives us a good basis of text classfication.

Data is parsed and gathered from these two popular reddit posts. Subsequently, these data are splitted into training and test data for modelling and evaluation using machine learning techniques.

In this project, we have used mainly the two classifer:

- Naive Bayes Classifier
- Logisitc Regression

After modelling of the two classifier, Naive Bayes Mutlinomial Classifier performed the best in terms of accuracy score. Misclassification rate for this model is relatively low and it appears to be the presence of some weighted words of other post appearing on the other.

In order to increase the performance of the model, further research on contextualising would needed to be performed. This would help to identify more important feature.



## Process

1. Data Gathering

   A. WebAPI

   B. PushShiftAPI

2. Data Cleaning and Pre-processing

3. EDA

4. Baseline Accuracy

5. Modelling

6. Model Evaluation

7. Limitation and Recommendation

8. Conclusion

## Limitation & Recommendation

We could potentially study misclassified post and including some of these words into stopwords to understand if there is any improvement in modelling.

- Identifying new stopwords
- Remodel and make comparison
- Exploring other classification model (e.g. RandomForest ..)

We could also further research on linguistic techniques to understand contextual of corpus so that post will not be misclassified.

## Conclusion



It is prominent that Naive Bayes model perform better than logistic regression. Amongst TfidVectorizer and CountVectorizer, the Naive Bayes with CountVectorizer model score better. Based on outside research, it could be because generative model (Naive Bayes) works better with little data. 
[https://stats.stackexchange.com/questions/273986/why-does-multinomial-naive-bayes-work-better-than-svm-and-logistic-regression-on]
[https://ai.stanford.edu/~ang/papers/nips01-discriminativegenerative.pdf]

In addition, we would propose to further investigate on techniques on how to contextualise texts and linguistic techinques to understand text.






