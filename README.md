# Sentiment Analysis in Twitter using Python (Python 2)

•	My aim is to analyse and visualize the opinion of people on any specified topic (specified by hashtag) based tweets extracted from   Twitter using that particular hashtag.
•	Basically we will categorize tweets into positive and negative based on the content of the tweet using natural language processing in python.


#Textblob

•	It is a natural language processing library in python.
•	TextBlob is a Python (2 and 3) library for processing textual data. It provides a simple API for diving into common natural language processing (NLP) tasks such as part-of-speech tagging, noun phrase extraction, sentiment analysis, classification, translation, and more.
•	For installation type the following command in terminal
$ pip install -U textblob
$ python -m textblob.download_corpora

#Twitter API

•	It is used to extract tweets from twitter in real time.

•	The Twitter API allows you to access the features of Twitter without having to go through the website interface. This can be useful for doing things like posting tweets or sending directed messages in an automated way with scripts.

•	We need to get the API keys from the official website www.devolopers.twitter.com by registering the project and it’s purpose.

Working

•	First we will get the input from the user for which he needs to get the opinions of users in twitter.

•	Then we need to access specified no. of tweets from twitter in real time using twitter API which is accessed by tweepy python library.

•	All tweets will be pre-processed: url in tweets are removed using regular expression.

•	Using textlob we will calculate the polarity of each tweets.

• store every tweet and it’s polarity in a pandas dataframe.

•	Consider the tweets with polarity>0 as positive tweets and polarity<0 as negative tweet.

•	Plot the graph- No.of Tweets vs Polarity graph using matplotlib library of python.

• Display the no. of positive and negative tweets











