# Twitter-datamining-Using-API
In this project i extracted data from twitter using tweepy and twitter API 
i cleaned the data and saved it in a CSV file

I analysed diffrent twittwer accounts to get total number of tweets and retweets,number of follwers number of friends
names of followers and friens
# EXPLANTION OF THE PROCESS, THE JUSTFACTION BEHIND IT, LESSONS LEARNED AND FINDING
EXPLANATION OF PROCESS
First step i installed tweepy and imported to my .ipynb file

Then i connected to My twiiter api using my consumer and access token keys

After the connection was established i tested by using command api.status

Then i extracted data of the last 300 tweets talking about bitcoin

After Data exration i stored it in a csv file where i started analysing

I created a pandas dataframe for my dataset for easy identification

I preprocessed my data

I performed data cleaning and then restore it in another csv file

Wow i started analysing data for the popular accounts that is Elon Musk,Bill Gates and Hillary clinton

# LESSONS LEARNED
I learned data mining using tweepy library

I learned that there are two versions of twitter API which have diffrent formants

I learned that You can use python tho tweet,retweet,like,unlike block users or do many of the functions a normal user does when using a computer

I learned to preprocess data and analyse it

I learned to clean data checkinf for missing data and dropping tables for missing data

# FINDINS
I analysed data of 3 accounts

i found out that elon musk has the highest number of followers followed by Bill Gates and the HIllary clinton

When i analysed how many they tweeted i realised Hillary clinton was leading followed by bill gates

My assumption was Elon Musk is more popular That Bill Gates and Hillary Clinton
# PART 2:NETWORK ANALYSIS

In this task i performed network analysis of my three influencers i.e Bill Gates,Elon Musk and Hillary clinton

First i had to find a number of their friends in this case i only printed 10 as inqured that i hade to used 10 for both

Then i used networkX to graphically represent my data which i mannually reprented

After calculating the statistics of my influencers my results were

## Bill Gates
▪ Degree Distribution=9

▪ Cluster coefficient=0

▪ Betweenness Centrality=1.0

▪ Assortativity=0.7071074555358021

## Hillary clinton
▪ Degree Distribution=8

▪ Cluster coefficient=0

▪ Betweenness Centrality=0.01818181818181818

▪ Assortativity= 0.7071067744546117

# LESSONS LEARNED
I learned how to used networkx to represent a particular network

I learned that Network analysis is an imporntant practice where it make me understand relationshis i.e Node and Edge ,parent and child

I learned that network analysis easly makes know how much an influencer is populer

I learned that We can also visualize the network such that the node color varies with Degree and node size with Betweenness Centrality

I learned that The Betweenness Centrality is the centrality of control. It represents the frequency at which a point occurs on the geodesic (shortest paths) that connected pair of points. It quantifies how many times a particular node comes in the shortest chosen path between two other nodes
