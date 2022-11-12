# IndustrialML_ITMO-1
Forecasting user activity in social networks in Saint Petersburg.
ITMO practical assignment



Social media occupies a very important place in modern human life and has a strong influence on daily life. A huge flow of information related to a person's thoughts, experiences, emotions, and the world that surrounds him/her is transmitted through them. Exploring social media streams allows you to observe processes taking place in the city, to predict emerging anomalies and events, allowing you to react to them in a timely manner. In this assignment you will learn how to use historical social network data about the frequency of publications in different urban areas to predict future distribution. 

We have a dataset of one popular social network that includes more than 8.5 million records with meta-information of publications over 13 months (January 2019 to February 2020). 

Each publication is described by the following meta-information: 

lon, lat – geoposition coordinates rounded up to a 250x250 meter polygon (geographical longitude and latitude, respectively) 

timestamp – timestamp of the publication accurate to one hour 

likescount – number of "likes" in the publication 

commentscount – number of comments of the publication 

symbols_cnt – number of all symbols in the publication 

words_cnt – number of words (meaningful, not counting special characters and other meta-information) 

hashtags_cnt – number of hashtags  

mentions_cnt – the number of mentions of other users 

links_cnt – number of links 

emoji_cnt – number of emoji. 

Using this data, you we needed to predict the number of publications in each 250x250 meter polygon for each hour 4 weeks (28 days) ahead of the last publication in the training set. 
