# WeRateDogs-Data-Analysis
We all love pets, and dogs are the most beloved. They are our best friends. WeRateDogs Twitter account has tons of photos for cute dogs. In this project we get a range of tweets using the API provided by twitter, and analyze the reactions to them.<br>
**Scope:**
We will analyze the tweets in time frame from Nov. 2015, to Aug. 2017. Each photo has its rating that expresses the user's opinion. But to get more insights we can analyze other people's interactions on the tweets. Interactions include favorites, retweets, and may be replies. But for this analysis, we will only consider the first favorites and retweets. Replies can vary, they may agree or not agree with the tweet, so it needs more complex analysis other than counting.<br>
**Data insights:**
The data sample includes 2356 tweet. 2075 of them have predictions of the dog type. However, after performing data cleaning, the number of tweets included in the analysis is 2092 tweet, after excluding replies and retweets as well as some tweets that don't have images or not related to dogs.
For time series analysis, I excluded those of August 2017, because the sample only includes first day of the month.
