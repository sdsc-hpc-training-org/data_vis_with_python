# Lesson 2

##Plot Tweet Timelines Using Bins and Interactive Bokeh Scatterplots

For this lesson we will generate timeline plots of individual tweets and all retweets for the most retweeted tweets using 5 minute (variable) bins and interactive Bokeh scatterplots with Botometer scores and follower counts.

In this lesson, we will do some simple plotting just using matplotlib to get an idea of what plotting is typically like in Python. Then we will add some pan/zoom interactivity to the plots using Bokeh. 

##About the data

This dataset was created earlier this year using the Twitter Streaming API searching for all tweets/retweets which use the hashtag 'muellerreport'. The original data was collected in its native JSON format. The JSON data comprised more than 5 GB. We reduced the size by extracting a subset of features, only a few of which we will need for this lesson. Here are some stats for the dataset.

Start: 2019-04-09 17:59:58

End: 2019-04-29 15:24:59

1,732,899 Total Tweets

1,420,964 Retweets

311,935 Original Tweets

