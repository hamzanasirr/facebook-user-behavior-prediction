# facebook-user-behavior-prediction using clustering
Let's say we want to identify certain groups of facebook users based on their behavior **using clustering**. Some facebook users might not react on the posts. Some people may 'like' react more and use other reactions like 'love' or 'wow' to a very minute extent. Some people may share posts a lot while some may not. Some only react and not comment on posts. Some may comment but react much, etc.  We are going to identify such groups with the help of machine learning.

We have a dataset of users' number of reactions (likes, wows, hahas, etc.), number of comments, shares, etc.

## Algorithm ##
Since, this is an unlabelled dataset. We need to find those labels (AKA clusters). Here I am using **K-Means Clustering** Algorithm.
