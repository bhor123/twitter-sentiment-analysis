# Twitter-Sentiment-Analysis

This script can tell you the sentiments of people regarding to any events happening in the world by analyzing tweets related to that event. It will search for tweets about any topic and analyze each tweet to see how positive or negative it's emotion is


## Getting Started
 
First of all login from your Twitter account and goto [Twitter Apps](https://apps.twitter.com/). Create a new app and goto __Keys and access tokens__ and copy Consumer Key, Consumer Secret, Access Token and Access Token Secret. We will need them later. 


### Usage

Once you have created an app on twitter Developer account , open main.py and paste your Consumer Key, Consumer Secret, Access Token and Access Token Secret. After that save and run the script.
For running the code , You have to write following command in terminal :
                             streamlit -run main.py
        replace main.py with the file name.
        
You will be prompted to enter the keyword/hashtag you want to analyze and the number of tweets you want to analyze. Once the analysis is completed, a pie chart will be generated disclosing the results of analysis And a tabula dataframe will be also generated.

## Built With

* Python 3.6
* tweepy
* textblob
* plotly
* pandas
* streamlit

## Authors

Bhor Sharma



