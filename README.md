# <center> NLP Sentiment Analysis 
# Reviews of a Photo Company


## 1.	Introduction

Natural Language Processing is a useful tool to analyze large amounts of text data for different purposes. A Photo Company provided its data and wanted to gain more information on how the reviews were actually worded. The company did not only want a basic classification of good and bad reviews but also how the customers felt about the products / services and how they expressed their feelings, which words they used the most. To excel in the service it provides, the company believes the word ‘good’ is not enough.

## 2.	Process

I started with data cleaning and wrangling, continued with Exploratory Data Analysis and text pre-processing. I used word clouds and other visualizations to gain insights from the data. 
Next, I employed 12 machine learning  algorithms to predict sentiments of customers, namely, Logistic Regression, K-Nearest Neighbors, Linear Support Vector Machines (SVM), Kernel SVM, Naive Bayes, Decision Trees, Random Forest, AdaBoost, Gradient Boosting, Stochastic Gradient Boosting, Extreme Gradient Boosting (XGBoost) and CatBoost. I used these algorithms with 7 different bag of words methods, i.e. Count Vectorizer, TfIdf Vectorizer, Hashing Vectorizer, SMOTE, PCA with SMOTE, Truncated SVD with SMOTE and Word2Vec.
Finally, I implemented deep learning models with Word2Vec, GloVe, FastText, Convolutional Neural Networks (CNN) and Recurrent Neural Networks (RNN) Long Short Term Memory (LSTM).

## 3.	Results

In short, top ten words used in positive reviews were: beautiful, good, quality, recommend, thanks, professional, smiling, glad and fast. In negative reviews top ten were: bad, expensive, never, prices, place, absolutely, money, even and wedding.
Best average F1 score of 85% achieved by Count Vectorizer with Naïve Bayes algorithm. 

![final results_1](https://github.com/gokaybulut/NLP_Sentiment_Analysis_Photo_Company/blob/master/4_Images/Final_Results_1.png)

![final_results_2](https://github.com/gokaybulut/NLP_Sentiment_Analysis_Photo_Company/blob/master/4_Images/Final_Results_2.png)
