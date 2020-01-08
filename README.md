# Twitter-Data-

Working with the Twitter page 'WeRateDogs' to access data and learning about Wrangle and Analysis

This is the forth project of Udacity Course. Since most of the data was given to us in the previous projects, this one focuses on the idea to use a certain API to gain/collect data and further work with it in the project. 

# Challange in the Way

Unfortunately, it was impossible for me to obtain the 'developer account' for Twitter. I have sent my application (with multiple email responds about WHY I need this account), but after a week of waiting for the verification I have decided to complete the project without obtaining the data online. Hence, I have downloaded a sample of **'twitter_api' and 'twitter_json'**

# Gathering 

Firstly, I need to download all the files. Luckily, all the data sets were privided to me by the Udacity course where I could download 'twitter_archive', 'twitter_api', 'twitter_json' and 'image_prediction'.

# Access 

As soona as we download all the data I need to make sure that I can view it. For that I use most common commands like .head, .tail, .info, and checking the data for ducplicates (.duplicated). By the end of Access, the most important part is to pinpoint what are the Quality and Tidiness issues. The udacity criteria suggests that we find atleast 8 Quality Issues and at least 2 Tidiness. As a results I end up with these Issues:

Quality:

1) Retweets are messing with the data (should be removed)
2) Some of the columns do not have enough data, thus it would be for better to remove them completely.
3) Remove the duplicated in the 'image_predictions' file
4) Timestamp is classified as an 'object' instead of 'datetime'
5) In archive, the Source column needs work as it is hard to understand the data
6) The 'stage' of the dog (puppo, pupper, floffer, doggo) can be modified
7) Image_predictions has a column p1 that has '_' inbetween word. Can be removed
8) In archive, some of the dog names are 'None' or written with mistake (a, the, 0, etc)

Tidiness:

9) Make all tweet_id equal to each other so that the data is more stable
10) Combine the data sets
11) Clean the combined data sets

# Analyse and Visualize 

As the data sets have been polished, some type of analysis and visual representation can be constructed to show some insights on the data itself. The three insights and one visual I decided to target would be:

- Most favorite Tweet?
- Highest retweeted tweet?
- How is the rating changing over time? (visual representation on this question)

