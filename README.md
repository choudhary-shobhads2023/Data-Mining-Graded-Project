# Data-Mining-Graded-Project

## Problem Statement 1
Clustering:

Digital Ads Data:

The ads24x7 is a Digital Marketing company which has now got seed funding of $10 Million. They are expanding their wings in Marketing Analytics. They collected data from their Marketing Intelligence team and now wants you (their newly appointed data analyst) to segment type of ads based on the features provided. Use Clustering procedure to segment ads into homogeneous groups.

The following three features are commonly used in digital marketing:

CPM = (Total Campaign Spend / Number of Impressions) * 1,000. Note that the Total Campaign Spend refers to the 'Spend' Column in the dataset and the Number of Impressions refers to the 'Impressions' Column in the dataset. 

CPC = Total Cost (spend) / Number of Clicks.  Note that the Total Cost (spend) refers to the 'Spend' Column in the dataset and the Number of Clicks refers to the 'Clicks' Column in the dataset. 

CTR = Total Measured Clicks / Total Measured Ad Impressions x 100. Note that the Total Measured Clicks refers to the 'Clicks' Column in the dataset and the Total Measured Ad Impressions refers to the 'Impressions' Column in the dataset. 

## Solution Approach
* Performed Data cleaning,Visualization and EDA part that is Necessary for any ML Algorithm.
* Performed all the necessary steps like Missing Value Treatment, Outlier Treatment ,Scaling of Data and others as per problem statement.
* Done Hierarchical Clustering on The data and Constructed Dendrogram for obtaining suitable no of Clusters.
* Plotted Elbow plot to identify optimum number of clusters for k-means algorithm.
* Calculated silhouette scores to identify optimum number of clusters.

## Problem Statement 2:
PCA:

PCA FH (FT): Primary census abstract for female headed households excluding institutional households (India & States/UTs - District Level), Scheduled tribes - 2011 PCA for Female Headed Household Excluding Institutional Household.The data collected has so many variables thus making it difficult to find useful details without using Data Science Techniques. We are tasked to perform detailed EDA and identify Optimum Principal Components that explains the most variance in data.

## Solution Approach:
* Performed Complete EDA, data claening,Visualization, etc..
* Performed all the required steps for PCA (use sklearn only).
* Identified the optimum number of PCs using Scree plot.
