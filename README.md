# Warframe-Tweet-NLP

In this project, I will scrape tweets about the game Warframe and do Natural Language Processing analysis on them, using spaCy and NTLK.


Files
Scrapers: I am scraping several different types of tweets from Twitter and storing them for import into data analysis. One script to scrape tweets by the official Warframe twitter account, and one script to scrape tweets using specific hashtags, in this case #warframe and #tennocon, relating to the Warframe game and annual Tennocon conference. 

These scraper files are the .py files listed below:
- scrapeWarframe.py: scrapes Twitter using account you enter (no @ sign), limited to 3240 tweets by Twitter
- scrapeHashtag.py: scrapes Twitter using hashtag you enter (no # sign), with number of tweets to scrape

The csv files of tweets created are the files listed below:
- PlayWarframe_tweets.csv - 3217 tweets as .csv file
- tweets_with_hashtag_TennoCon.csv - 1000 tweets as .csv file #TennoCon
- tweets_with_hashtag_warframe.csv - 1000 tweets as .csv file #warframe

Jupyter Notebooks: Once I have the tweets scraped, I will import them into Jupyter Notebooks to do NLP analysis on them.



This is a work in progress.

