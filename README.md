# Health-Pass-Tweets-Data-Analysis
**Project Objective:** to apply data analysis on tweets that talked about the Health Passport. 

**For detailed description of the project please read my article [Data Analysis on Health Passport Tweets](https://kheirie-elhariri.medium.com/data-analysis-on-health-passport-tweets-6732660324f3)**
## [DataAnalysis_PassSanitaire.ipynb](https://github.com/kheirie/Health-Pass-Tweets-Data-Analysis/blob/main/DataAnalysis_PassSanitaire.ipynb) Notebook
This notebook details the steps taken to apply data analysis on Health Passport Tweets. 
## [Scrape_Abbreviations.ipynb](https://github.com/kheirie/Health-Pass-Tweets-Data-Analysis/blob/main/Scrape_Abbreviations.ipynb) Notebook
This notebook covers the steps to scrape this [website](https://www.noslang.com/dictionary/1/) in order to create a slang dictionary. The slang dictionary is used in the text preprocessing section in the *DataAnalysis_PassSanitaire.ipynb* to convert slangs to their full form.
## [Twitter_API_Tweets_Extraction.ipynb](https://github.com/kheirie/Health-Pass-Tweets-Data-Analysis/blob/main/Twitter_API_Tweets_Extraction.ipynb) Notebook 
This notebook shows the steps taken to extract the tweets. Creating a [twitter developer account](https://developer.twitter.com/en/apply-for-access) and acquiring keys and tokens are essential to retrieve data through twitter. 
## Results 
### Location Analysis 
The objective of the location analysis is to obtain a general overview from where the tweets originated by calculating the number of tweets per country.

![alt text](https://github.com/kheirie/Health-Pass-Tweets-Data-Analysis/blob/main/data/images/no_of_tweets_per_country(1).png "Map-Number of Tweets per Country")
### Tweets Text Analysis 
The objective of the tweets text analysis is to get a glimpse into the most used terms in the tweets through unigrams, bigrams and trigrams. Unigrams were displayed through a word cloud, whereas bigrams and trigrams were displayed through a bar graph. 
#### Word Cloud

![alt text](https://github.com/kheirie/Health-Pass-Tweets-Data-Analysis/blob/main/data/images/tfidf_ps_word_cloud.png "tfidf_wordcloud") 
#### Bar Graphs of Top 100 Bigrams and Trigrams

![alt text](https://github.com/kheirie/Health-Pass-Tweets-Data-Analysis/blob/main/data/images/Top%20100%20Bigrams.png "top 100 bigrams") 

![alt text](https://github.com/kheirie/Health-Pass-Tweets-Data-Analysis/blob/main/data/images/Top%20100%20Trigrams.png "top 100 trigrams") 
