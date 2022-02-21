# MEPs' Tweets Classification
We investigated a dataset of tweets made by Members of the European Parliament. We used data collected by Darko Cherepnalkoski, Andreas Karpf, Igor Mozetič, and Miha Grčar for their paper Cohesion and Coalition Formation in the European Parliament: Roll-Call Votes and Twitter Activities.

In particular, the dataset was obtained from https://www.clarin.si/repository/xmlui/handle/11356/1071. We used the "retweets.csv" file and kept only the records where the original tweet was written in English. We also obtained the original tweet's text and added it as an extra column to the dataset. We only kept the records for which we were able to download the tweet text. We grouped the records by the European group of the MEP who posted the original tweet, and we removed the groups with a small number of tweets (i.e. less than 50).


Text representation (Bag of Words methods)¶
1) Bag of word matrix
2) TF-IDF Vectors
•	a] Word level
•	b] N-Gram level
•	c] Character level


