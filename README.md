# Structured-Streaming-of-Tweets

We will be streaming live tweets from twitter related to a particular topic. In our example we have streamed tweets related to the topic "soccer" and displayed those on our terminal. Once this is done we segregate them by words to filter the words staring with a hashtag i.e.#. We do this as we want to figure out the trending hashtags in the tweets that are related to soccer.

We display the tweets on one console and the trending hashtags on another one.

### Two files have been used to do the above mentioned tasks:
 1. TweetRead.py
 2. StructuredStreaming.ipynb
 
###### TweetRead.py:This file is used to import all the tweets related to soccer from twitter and display them on the console through sockets. To import the tweets one has to create a twitter developer account which enables us to perform the import action using the TWitter API Keys.
 
###### StructuredStreaming.ipynb: This jupyter notebook performs the action of displaying the trending hashtags by loading the stream  and segregating the words.

##### P.S.:- We perform the above opertaions using PySpark and Tweepy.
 
 ![ezgif com-optimize](https://user-images.githubusercontent.com/47166154/79394751-36ad8080-7f46-11ea-9b93-315ad49d37a7.gif)
