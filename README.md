# Portfolio

## [Sentiment Analysis of Killing Eve TV Series :thumbsup:](https://github.com/Alicja96/Sentiment-Analysis-of-Killing-Eve-TV-Series.git)
Tools: beautifulsoup, selenium, requests, pandas, nltk, langdetect, plotly, scikit-learn, imblearn, textblob, wordcloud

Performed web scraping to extract reviews of popular tv series to predict their polarity using lexicon-based approaches (TextBlob, VADER) and machine learning classifiers such as Naive Bayes, SVM, and Logistic Regression while dealing with imbalanced data. 

filename | description
------------ | -------------
[WebScrapingIMDBReviews.py](https://github.com/Alicja96/Sentiment-Analysis-of-Killing-Eve-TV-Series/blob/master/WebScrapingIMDBReviews.py)| Used selenium and beautifulsoup to extract reviews from IMDB website. 
[RottenTomatoesAudienceReviews.py](https://github.com/Alicja96/Sentiment-Analysis-of-Killing-Eve-TV-Series/blob/master/RottenTomatoesAudienceReviews.py)| Scraped audience reviews from RottenTomatoes website by using selenium and beautifulsoup. 
[RottenTomatoesCriticsReviews.py](https://github.com/Alicja96/Sentiment-Analysis-of-Killing-Eve-TV-Series/blob/master/RottenTomatoesCriticsReviews.py) | Extracted reviews from critics from RottenTomatoes with use of beautifulsoup and requests library. 
[SentimentAnalysisKillingEve.ipynb](https://github.com/Alicja96/Sentiment-Analysis-of-Killing-Eve-TV-Series/blob/master/SentimentAnalysisKillingEve.ipynb) | Conducted data pre-processing and cleaning by removing stop words, punctuation, numbers and detected language of each review, calculated sentiment score of each review by comparing it’s tokens with positive and negative lexicon. Applied Multinomial Naive Bayes and Stochastic Gradient Descent Classifier with Tf-idfVectorizer, CountVectorizer and performed over-sampling using SMOTE. Used GridSearchCV to find the optimal parameters.


## [Word Frequency in Star Wars Movies :speech_balloon:](https://github.com/Alicja96/Word-Frequency-in-Star-Wars.git)

 Tools: beautifulsoup, requests, pandas, nltk, plotly
 
 The purpose of this project is to find out what are the most frequent words in Star Wars movies and how often they occur.
 
 filename | description
------------ | -------------
[WebScrapingTranscripts.py](https://github.com/Alicja96/Word-Frequency-in-Star-Wars/blob/master/WebScrapingTranscripts.py) | Used beautifulsoup and requests library to extract transcripts of Star Wars movies. 
[WordFrequencyStarWars.ipnyb](WordFrequencyStarWars.ipynb) | Contains analysis of the distribution of words in Star Wars movie transcripts with the use of Natural Language ToolKit(nltk).


## [Insurance Cost Predictions :hospital:](https://github.com/Alicja96/Insurance-Cost-Predictions)

Tools: pandas, plotly, scikit-learn, matplotlib, seaborn, yellowbrick

Applied regression techniques to predict medical insurance costs for individuals and used GridSearchCV to find the optimal parameters.

filename | description
------------ | -------------
[InsuranceCostPredictions.ipynb](https://github.com/Alicja96/Insurance-Cost-Predictions/blob/master/InsuranceCostPredictions.ipynb)| Exploratory data analysis and predictions of medical insurance costs with machine learning algorithms such as LinearRegression, PolynomialRegression, ElasticNet, RandomForestRegressor, DecisionTreeRegressor and hyperparameter tuning with GridSearchCV. 

## [Baltimore Crime Analysis :police_car:](https://github.com/Alicja96/Baltimore-Crime-Analysis)

Tools: plotly, pandas, matplotlib, seaborn

filename | description
------------ | -------------
[Baltimore_Crime_Analysis.ipynb](https://github.com/Alicja96/Baltimore-Crime-Analysis/blob/master/Baltimore_Crime_Analysis.ipynb)| Exploratory Data Analysis of Baltimore Crime Data from 2012-2016.
