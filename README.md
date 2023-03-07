# Tweets Dataset on the Ghanaian 26-man squad and backroom staff members for the 2022 FIFA world cup.

This repository contains IDs of tweets that were sent to the twitter account of the selected Ghanaian 26-man squad and backroom staff members during the FIFA world 2022 at Qatar. We are sharing only tweet ID's in order to comply with the [Terms and Conditions of Twitter](https://developer.twitter.com/en/developer-terms/agreement-and-policy) regarding the sharing of tweets.

# Data Organization
* On November 18, 2022, we began our dataset collection with the Twitter streaming API and a python library, Tweepy.
*	Tweet-ID files are group into four files, which is the 26 players, backroom staff members, GFA, and the national team [Number of Tweets](images/figure1.png).

# Dataset collection
* Tweets were collected from November 18th to December 3rd 2022.
* The tweets were collected using the official Twitter account names of the players, their known names or nicknames and other hashtags.The Account name and searched keywords folder contains a list of the 26-man squad, number of tweets and their keywords used in generating the tweets.
* Tweets can be fully collected using the following tools [Hydrator](https://github.com/DocNow/hydrator)  and [twarc](https://github.com/DocNow/twarc).

# Dataset Statistics
The following are the collective summary if the dataset<br/>
Statistics	Frequency<br/>
Number of Tweets:	132,115<br/>
Number of duplicate tweets:	13,625<br/>
Number of Unique tweets:	118,490<br/>
Number of Retweets:	22,448<br/>
Average number of tweets per day:	8,260 [](images/figure2.png)<br/>
Average number of tweets per player:	2520<br/>
Tweets with location:	91,256

* [Dataset wordcloud](images/wordcloud.png)

# Acknowledgement
* This work was made possible by Dr. Rose-Mary Gyening, Dr. Kate Takyi and  Sarah Alqurashi
 
