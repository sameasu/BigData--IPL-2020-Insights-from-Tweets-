# BigData--IPL-2020-Insights-from-Tweets-
This project was part of the course in Big Data Engineering at Jio Institute.
Idea is apply map-reduce thinking in the project.
Project was carried on Databricks community edition.

Instructions for the Project:

1. Solve the problems given in the Insights section using **map-reduce** steps only.
2. Use of Pandas library or other Dataframe APIs like Spark Dataframe APIs shall NOT be done. 
3. **Databricks** platform must be used for this assignment.
4. Upload the data file to the location: /FileStore/tables/jio2025/Sample_tweets.csv
5. Use PEP8 standards for coding (Refer to link).
6. The notebook should have the Names and IDs of all members of your group at the
beginning.

**Insights**

1. Find top 5 hashtag trends for different months. The results should be in the following format:
      Month, rank, Hashtag, number of tweets
2. Find the trends of tweets (number of tweets) for each team over different months. The results should have
      a. Team name, month, number of tweets
      b. A list of abbreviated names of the teams can be used to filter tweets (e.g. CSK,MI, RCB etc.)
3. Identify the top 5 tweets for each hashtag, ordered by the number of followers the users have, who have tweeted. It should contain       unique set of users. The result should contain:
      Hashtag, list of 5 tweets, the username who has tweeted and the number of followers.
4. Create an inverted index of hashtags and the tweets so that given a hashtag, you can print the list of tweets with the hashtags          sorted by the months. The result should contain
       Hashtag, month, list of tweets (actual text)
5. Define 3 Insights of your own.
   a. Checking monthwise which location has maximum number of tweets
       Output: Month, User Location, Number of Tweets
   b. Which team has maximum team from which location
       Output: Team wise: Number of tweets, City Location
   c. Which proportion of source in the tweets
       Output: Number of Tweets, Source
