# Time_Series_Clustering
This repository is based on the Time series clustering problem. 

# Dataset Used
https://drive.google.com/file/d/1pP0Rr83ri0voscgr95-YnVCBv6BYV22w/view

# There are three problem that i have tried to solve in this problem.

Problem 1:

    There are various stocks for which we have collected a data set, which all stocks are apparently similar in performance

Problem 2:

    How many Unique patterns that exist in the historical stock data set, based on fluctuations in price.

Problem 3:
    Identify which all stocks are moving together and which all stocks are different from each other.


Proposed Solutions: -
For problem 1: - 


  There are basically 3 ways to identify the similar stocks according to the performance:


    1) using Correlation coefficient

    2) using K-menas clustering

    3) PCA algorithm
    
 For Problem 2: - 
 
 
  WE can use k means clustering for cluster out the different patterns that exist in the dataset.we have 5 different unique patterns that exist in out dataframe out of them cluster 1 has the maximum number of stock availble with similar patterns. 
  
  For problem 3: -
    I have used PCA algorithm in order to solve this problem. 

Conclusion: we can see that group 0 has kind of similar plot while group 2 plots has very different , so we can say that there are approximetly 68 different stocks which are moving in same direction.

