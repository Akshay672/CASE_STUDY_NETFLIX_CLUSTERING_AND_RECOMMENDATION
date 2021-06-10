# NETFLIX CLUSTERING AND RECOMMENDATION
# Problem Statement:

A study on unsupervised learning techniques(Clustering & Recommendation), market basket analysis and recommendation systems on 'Netflix Titles'.

<img src="tenor.gif" width="750" align="center">



# About this Dataset:

TV Shows and Movies listed on Netflix
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010.

# Column Description:

![image](https://user-images.githubusercontent.com/85668824/121569207-2a379180-ca3e-11eb-898d-3af0ac3bbffe.png)


# Task Completed:

Import Libraries

Data Preparation

2.1 - Data Interpretation
2.2 - Missing Value Treatment

Exploratory Data Analysis

Data Cleaning

4.1 - Replacement
4.2 - Scale the Data

Clustering

5.1 - K Mean Clustering

5.1.1 - Optimal value of K using Elbow Plot

5.1.2 - Optimal value of K using Silhouette Score

5.1.3 - Visualizing the Silhouette Score

5.1.4 - Building the Cluster

5.1.5 - Analyzing the Cluster

5.2 - Hierarchical Clustering

5.2.1 - Model Building

5.2.2 - Dendrogram Plot

5.2.3 - Cutting the Trees

5.2.4 - Silhouette Score Method

5.2.5 - Retrieving the Cluster

Recommendation Systems

3.1 - Popularity Based Approach

3.2 - Content Based Recommendation

# Conclusion :


1) We used a Netflix Dataset with Movies constituting 69.1% and TV Shows constituting 30.9%.

2) Netflix's content is divided into several categories that targets Adults, Teens, Older kids and Kids.

3) We used the K means and Hierarchical Clustering Algorithms to cluster our data.

4) The optimal number of clusters we obtained is 2. Using this we built the Clusters and observed the following

   The Average Reviews from Users on TV Shows are more compared to Critics.

   Average IMDB US Voters Rating on TV Shows are more compared to IMDB Non-US Voters as goes with Movies.

   Average IMDB US Voters on TV Shows are more compared to Movies indicating marginal preference of US Voters to TV Shows.

5) On the basis of Popularity Based Approach

   The highest rated shows and movies on Netflix are not suitable for children below the age of 17.

   Average reviews from Netflix Users is more as compared to that of Critics.

   US Raters give a higher Rating compared to Non US Raters.

6) On the Basis of Content Based Approach

   We noted that Netflix could Recommend 5 Movies and TV Shows based on customer Interests.

<h4>DATASET FILE LINK : <a href='https://www.kaggle.com/shivamb/netflix-shows'>netflix_titles.csv</a></h4>


<h4>CASE STUDY FILE LINK : <a href='https://github.com/Akshay672/CASE_STUDY_NETFLIX_CLUSTERING_AND_RECOMMENDATION/blob/main/NETFLIX_CLUSTERING_AND_RECOMMENDATION.ipynb'>NETFLIX_CLUSTERING_AND_RECOMMENDATION.ipynb</a></h4>
