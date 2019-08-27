# HongKongProtest-Tweet-NLP

In this project, I will scrape tweets about the 2019 Hong Kong Protests and do Natural Language Processing analysis on them, using spaCy and NTLK.


Files
Scrapers: I am scraping several different types of tweets from Twitter and storing them as csv files for import into dataframes for data science analysis. I created a script to scrape tweets using specific hashtags, in this case #hongkong, #hongkongprotests,, #antiELAB, and #yuenlong relating to the protests and events in Hong Kong. 

These scraper files are the .py files listed below:
- scrapeHashtag.py: scrapes Twitter using hashtag you enter (no # sign), with number of tweets to scrape

The csv files of tweets created are the files listed below:
- tweets_with_hashtag_honglong.csv - 3000 tweets as .csv file (some of these may not be protest related)
- tweets_with_hashtag_yuenlong.csv - 3000 tweets as .csv file 
- tweets_with_hashtag_hongkongprotests.csv - 3000 tweets as .csv file
- tweets_with_hashtag_antiELAB.csv - 3000 tweets as .csv file 

These tweets were all scraped from the timeframe of XXXX when I started the project.

Jupyter Notebooks: Once I have the tweets scraped, I will import them into Jupyter Notebooks to do NLP analysis on them.

This is a work in progress.

