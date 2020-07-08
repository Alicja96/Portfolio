# Portfolio

## [Sentiment Analysis of Killing Eve TV Series :thumbsup:](https://github.com/Alicja96/Sentiment-Analysis-of-Killing-Eve-TV-Series.git)
Tools: beautifulsoup, selenium, requests, pandas, nltk, langdetect, plotly, scikit-learn, imblearn, textblob, wordcloud

Performed web scraping to extract reviews of popular tv series to predict their polarity using lexicon-based approaches (TextBlob, VADER) and machine learning classifiers such as Naive Bayes, SVM, and Logistic Regression while dealing with imbalanced data. 

filename | description
------------ | -------------
[WebScrapingIMDBReviews.py](WebScrapingIMDBReviews.py)| Used selenium and beautifulsoup to extract reviews from IMDB website. 
[RottenTomatoesAudienceReviews.py](RottenTomatoesAudienceReviews.py)| Scraped audience reviews from RottenTomatoes website by using selenium and beautifulsoup. 
[RottenTomatoesCriticsReviews.py](RottenTomatoesCriticsReviews.py) | Extracted reviews from critics from RottenTomatoes with use of beautifulsoup and requests library. 
[SentimentAnalysisKillingEve.ipynb](SentimentAnalysisKillingEve.ipynb) | Conducted data pre-processing and cleaning by removing stop words, punctuation, numbers and detected language of each review, calculated sentiment score of each review by comparing it’s tokens with positive and negative lexicon. Applied Multinomial Naive Bayes and Stochastic Gradient Descent Classifier with Tf-idfVectorizer, CountVectorizer and performed over-sampling using SMOTE. Used GridSearchCV to find the optimal parameters.


## [Word Frequency in Star Wars Movies :speech_balloon:](https://github.com/Alicja96/Word-Frequency-in-Star-Wars.git)

 Tools: beautifulsoup, requests, pandas, nltk, plotly
 
 The purpose of this project is to find out what are the most frequent words in Star Wars movies and how often they occur.
 
 filename | description
------------ | -------------
[WebScrapingTranscripts.py](WebScrapingTranscripts.py) | Used beautifulsoup and requests library to extract transcripts of Star Wars movies. 
[WordFrequencyStarWars.ipnyb](WordFrequencyStarWars.ipynb) | Contains analysis of the distribution of words in Star Wars movie transcripts with the use of Natural Language ToolKit(nltk).

## Cryptocurrency Price Prediction :chart_with_upwards_trend:

Tools: requests, plotly, pandas


## Medical Personal Cost  :hospital:

Tools: pandas, scikit-learn

In this project, I will apply regression techniques to predict medical insurance costs for individuals.


## Baltimore Crime Analysis :police_car:

Tools: plotly, pandas, matplotlib

In this project, I am going to explore more about crime in Baltimore and try to answer the following questions:
* Which crimes are most frequently committed? 
* How has the number of crimes changed over time in Baltimore? 
* What category of crimes were increasing and which were decreasing over time?
* Which of the Baltimore Districts had an increasing and which had a decreasing amount of crime events? 
* Are there certain high crime locations for certain crimes?  
* Which season was getting the most crimes? 
* Which part of a day most of the crimes were committed? 
* Which day of the week had the highest rate of committed crimes?
* Were the majority of crimes committed outside or inside?

