# Bachelorthesis---Sentiment-Analysis-with-Deep-Learning
This study analysed the sentiment of tweets of political candidates in the 2016 U.S. Presidential election.
In order to run the code, change the path of the loaded model when performing analysis of Tweets. Also change the paths of datasets.


File description:
model - the old, weaker model trained on 5 epochs

model_new - the new, stronger model, trained on 80 epochs

2016_us_election_tweets_100k.csv - this is the model on which the sentiment analysis was performed

Training-Copy1.ipynb - is the training notebook trained with 80 epochs

Training.ipynb - the exact same training notebook, training the model on 5 epochs

tweets_clinton_trump.csv - dataset containing about 6600 posts of Trump and Clinton before the election.

Visualization of Tweets - This is the visualization of Tweets using the weaker model. This notebook uses the tweets_clinton_trump.csv dataset.

train.csv - is the training dataset containg Tweets that were labelled for training - positive, negative or neutral.

visualisation_of_people_tweets-Copy2.ipynb - notebook containing the analysis using the newer model. it visualizes the sentiment.

visualisation_of_people_tweets.ipynb - the same notebook using the weaker model.
