# Reddit discussions classification

### Mini Project 2 - Applied Machine Learning [COMP-551] - McGill - Winter 2017

The goal is to devise a machine learning algorithm to analyze short conversations extracted from [Reddit](https://www.reddit.com/), and automatically classify them according to their topics, which include _hockey, movies, nba, news, nfl, politics, soccer and worldnews_.<br>

Provided data is as follows: 
 - The training set consists of approximately 160,000 conversations. 
 - The test set consists of approximately 50,000 conversations. 
 - Only training labels are provided.<br>
 
 [Here](Project_2_Reddit_discussions_classification_NB.ipynb), a hard coded naive Bayes classifier has been implemented then compared to Scikit's MultinomialNB in addition to grid search to optimize classifier's parameters. A [neural network classifier](Classification_using_Keras.ipynb) using Keras has been implemented also as well as a [words cloud visualization](WordClouds.ipynb).
 
 ![nba_wordcloud](https://user-images.githubusercontent.com/44270915/47312701-0a43cd00-d60b-11e8-80ca-9ea711f53d19.png)
