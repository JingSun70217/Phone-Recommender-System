



# Phone Recommender System 


Recommend phone based on the sentiment analysis results which get from tweets.


## Phase I: Crawl phone-related tweets from Twitter

Thanks to the repository `GetOldTweets-python-master`. We could crawl the recent tweets according to our keywords.

Usage example:

>1. command when crawling data for iphone : python Exporter.py --since 2017-12-01 --until 2018-01-01 --querysearch "iphone and phone" --toptweets (change the dates accordingly)
>2. command when crawling data for lenovo : python Exporter.py --since 2017-11-01 --until 2017-12-01 --querysearch "lenovo and phone" --toptweets (change the dates accordingly)


## Phase II: Preprocessed tweets 

Preprocessed tweets with Natural Language Processing technologies and data mining methods.

## Phase III: Sentiment Analysis
Implemented the sentiment analysis and deep learning models on the preprocessed tweets. 

Sentiment Annotation tooling:
>client = textapi.Client("App ID", "Key") (enter your own APP ID and Key got on  [https://developer.aylien.com](https://developer.aylien.com/)

## Phase IV: Recommend phones
 Recommended top ranked phones based on the results of sentiment analysis.


