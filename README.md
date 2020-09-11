# Azubi-Hackathon
Azubi Hackathon is a project in which we provide **Sentiment Analysis** on the 2020 Ghana Presidential Election using data obtained from twitter feeds.
This Repo was created by [Michael Sekyere](https://www.linkedin.com/in/michael-sekyere-0a4898193/ "Michael Sekyere"),
[Razack Abubakar](https://www.linkedin.com/in/razack-abubakar-853160156/ "Razack Abubakar") and
[Ama Owusu-Darko](https://www.linkedin.com/in/aowusuda/ "Ama Owusu-Darko") as our capstone project as part of our training in Data Science in
the Azubi Africa Graduate Programme

## Introduction
* **Natural Language Processing (NLP)**: This is a discipline of artificial intelligence, linguistics and computer science that is concerned with the creation of computational models that process and understand natural languages.The ultimate objective of NLP is to make the computer read, decipher, understand, and make sense of the human languages in a manner that is valuable. Most NLP techniques rely on machine learning to derive meaning from human languages.

* **Sentiment Analysis**: It is the interpretation and classification of emotions(positive, negative or neutral) within text data using text analysis techniques. Sentiment analysis is helpful in allowing organizations to identify the public reaction to product, a message or an ideology, etc. For a political party, they can use sentiment analysis to to identify their campaign strategy and manifesto altogether

## Data Gathering
Data for the Analysis were gathered from twitter. Initially we created a Twitter Developer account, but there are limitations to it. You can not mine tweets older than 7 days, using twitter's rest API, unless you pay and even when you do, you are restricted to a limit of 100 tweets daily. Through research we came accross [Optimized-modified-GetOldTweets3-OMGOT](https://github.com/marquisvictor/Optimized-Modified-GetOldTweets3-OMGOT "Optimized-modified-GetOldTweets3-OMGOT") which is an improvement  of the original GetOldTweets Library by [Jefferson-Henrique](https://github.com/Jefferson-Henrique/GetOldTweets-python/ "Jefferson-Henrique"). With this we were able to bypass the limitations of using tweepy. Downloaded data and brief descriptions of them can be found on this [link](https://github.com/mickysekyere/Azubi-Hackathon/blob/master/Data/Data.md "link").

## Data Analysis
General descriptions of the datasets ie. the different files, what each column represent, etc has already been discussed in the **Data Gathering** portion of this README. Our analysis was done on three folds each suitable to the type of data collected. 
  ### Analysis 1 : General Overview
  In this notebook, we analysed tweets from some political accounts from the NPP and NDC. 6 Specific account whose tweet were analysed are the current president 
  HE. Nana Akufo-Addo, his running mate Dr. M. Bawumia, the official twitter handle of the New Patriotic Party, the opposition flagbearer Ex President John D. Mahama,
  his running mate Prof. Jane Naana O. Agyemang and the official twitter handle of the National Democratic Congress.
  Emphasis was laid on  identifying
  * How the public react to tweets from NPP and NDC based account by considering the retweets, favourites (likes) and the number of comment on them
  * Time series analysis detailing observable changes to how the political parties are using social media platforms as the election draws nearer
  * Word Cloud which gives us information on the kind of message the political parties are spreading.
  * General Sentiment to determine the amount of positivity in the tweets of political leaders in Ghana
  
  ### Analysis 2 : Hashtag Analysis
  In this notebook, we analysed several tweets containing the hashtags of the two political parties. For the NPP, tweets sampled contained various hashtags such as
  **#4More4Nana**, **4MoreToDoMore4You** whiles for NDC, their trending hashtag is **#JMandJane2020**, **#JDMahama2020** among others. The focus of our analysis was in  identifying
  * The trend in the growing number of tweets containing hashtags pertaining to a political party
  * The variation in the different number of people who activily follows each political party
  * On what days where there a significant amount in the hastag tweets for a particular party and what contributed to such spikes.
  
  ### Analysis 3 : Sentiment Analysis
  In this notebook, we analysed tweets which mentions the flagbearers of the two political parties and performed a sentiment analysis on them using textblob. The insight
  we obtained was fascinating as it was different from the general notion we all had.
  
  **Links to notebooks**
  1. [General Overview](https://github.com/Jefferson-Henrique/GetOldTweets-python/ "General Overview")
  2. [Hashtag Analysis](https://github.com/Jefferson-Henrique/GetOldTweets-python/ "Hashtag Analysis")
  3. [Sentiment Analysis](https://github.com/Jefferson-Henrique/GetOldTweets-python/ "Sentiment Analysis")

## Project Summary and conclusion
Summary and conclusion of project can be found in our [Presentation](https://github.com/mickysekyere/Azubi-Hackathon/blob/master/hackathon%202020.pptx "Presentation") as well as in our [Documentation](https://github.com/mickysekyere/Azubi-Hackathon/blob/master/Hackathonword%202020.docx "Documentation")
