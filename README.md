# NLP with disater tweets
Performed EDA , feature engineering and NPL on more than 10,000 tweets to identify disasters occurrence, 
built models by integrating BERT model with logistic regression and SVM, the best model yielded 83% accuracy.

## Data Description
A [Kaggle](https://www.kaggle.com/c/nlp-getting-started/data) competetion dataset that contains 10878 rows and columns as follow:
- id - a unique identifier for each tweet
- text - the text of the tweet
- location - the location the tweet was sent from (may be blank)
- keyword - a particular keyword from the tweet (may be blank)
- target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)

## Steps
1. Exploratory data analysis on location, keyword and text columns
2. Extracted mega features such as numbers of top keywords, tags and urls
3. Built language model using BERT and output prediction value as one of the features
4. Built another on all the features using LR and SVM, trained and evaluated the model
