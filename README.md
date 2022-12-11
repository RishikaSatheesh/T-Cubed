# T-Cubed -TWITTER SENTIMENT ANALYSIS
Project in Data Analytics.

Team members:
Rishika Satheesh
Minal H. R
Sneha S
Rajarajeshwari Murugan

Twitter sentiment analysis is a way of analysing a big pile of  tweets (train.csv) and generating a  model that detects negative, non negative tweets(racist or sexist and so on) and classifies it accordingly with highest accuracy.

This can be used in multiple real life situations, for example, to detect if a customer is happy or dissatisfied with a particular product, the impact of a famous celebrity on fans, to detect homophobic and racist insults or threats directed at people, and so on.

In the train.csv dataset we used , the coulums are tweets and labels, where label ‘1’ denotes the tweet is racist/sexist and label ‘0’ denotes the tweet is not racist/sexist, our objective is to predict the labels on the given test dataset.

Word Clouds is also used to visualize the most frequent words or popular phrases appearing most frequently in the dataset.

Sentiment analysis is an NLP technique, where we perform feature generation, preprocessing etc to perform analysis on large amounts of natural language data. And taking it further, we train our pre-processed data under the classifier models- Logistic Regression and Naïve Bayes. Performance is evaluated and then, is taken forward for testing as a step to success! (test.csv).

The final model will be able to smoothly classify a bunch of tweets to finally meet up to our expectations.

Since the problem is a classification problem, the models that we built here are using Logistic Regression and Naive Bayes.

In logistic regression model, the metric used are f1-score and accuracy-score, f1-score is used beacuse it balances the positive and negative tweets.On doing so, we get f1_score = 0.49 and accuracy = 94%
By using probability and threshold wecan increase the f1_score = 0.55, whereas accuracy remains the same

In Multinomial Naive Bayes classifier, the metrics that we chose are confusion matrix(with true labels in x-axis and pediction labels in y-axis) and accuracy score. On doing so, we get an accuracy of around 92%

END NOTES:
In this article, we learned how to approach a sentiment analysis problem. We started with preprocessing and exploration of data. Then we extracted features from the cleaned text using Bag-of-Words and TF-IDF. Finally, we were able to build a couple of models using both the feature sets to classify the tweets.
