# NETFLIX CLUSTERING AND RECOMMENDATION
<h2><font color='#b20710'>Problem Statement:</font></h2>
<h3><font color='#b20710'>A study on unsupervised learning techniques(Clustering & Recommendation), market basket analysis and recommendation systems on 'Netflix Titles'.</font></h3>

<img src="https://github.com/Akshay672/CASE_STUDY_NETFLIX_CLUSTERING_AND_RECOMMENDATION/blob/main/tenor.gif" width="750" align="center">


<h2><font color='#b20710'>About this Dataset</font></h2>
<h3><font color='#b20710'>TV Shows and Movies listed on Netflix</font></h3>

<h4>This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.<br>

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. 
<br><br>The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.
    
<br>
Integrating this dataset with other external datasets such as IMDB ratings and votes interesting findings.
</h4>
<h3><font color='#b20710'>Some of the interesting questions (tasks) which can be performed on this dataset -</font></h3>
<h4>
Understanding what content is available in different countries<br><br>
Identifying similar content by matching text-based features<br><br>
Is Netflix has increasingly focusing on TV rather than movies in recent years.</h4>
<h3><font color='#b20710'>Column Description</font></h3>

![image](https://user-images.githubusercontent.com/85668824/121569207-2a379180-ca3e-11eb-898d-3af0ac3bbffe.png)


  ## Task Completed:

1. **[<font color='#b20710'>Import Libraries</font>](#lib)**


2. **[<font color='#b20710'>Data Preparation</font>](#prep)**

      2.1 - **[<font color='#b20710'>Data Interpretation</font>](#datainter)**   
      2.2 - **[<font color='#b20710'>Missing Value Treatment</font>](#missval)**
      
      
3. **[<font color='#b20710'>Exploratory Data Analysis</font>](#eda)**


4. **[<font color='#b20710'>Data Cleaning</font>](#Dataclean)**

      4.1 - **[<font color='#b20710'>Replacement</font>](#replace)**     
      4.2 - **[<font color='#b20710'>Scale the Data</font>](#scale)**
      
      
5. **[<font color='#b20710'>Clustering</font>](#clus)**

      5.1 - **[<font color='#b20710'>K Mean Clustering</font>](#kmean)**
      
      5.1.1 - **[<font color='#b20710'>Optimal value of K using Elbow Plot</font>](#elbow)**
      
      5.1.2 - **[<font color='#b20710'>Optimal value of K using Silhouette Score</font>](#kss)**
      
      5.1.3 - **[<font color='#b20710'>Visualizing the Silhouette Score</font>](#vissil)**
      
      5.1.4 - **[<font color='#b20710'>Building the Cluster</font>](#buildclus)**
      
      5.1.5 - **[<font color='#b20710'>Analyzing the Cluster</font>](#anaclus)**
                
      5.2 - **[<font color='#b20710'>Hierarchical Clustering</font>](#hierar)**
      
      5.2.1 - **[<font color='#b20710'>Model Building</font>](#modbuild)**
      
      5.2.2 - **[<font color='#b20710'>Dendrogram Plot</font>](#dendro)**
      
      5.2.3 - **[<font color='#b20710'>Cutting the Trees</font>](#cuttree)**
      
      5.2.4 - **[<font color='#b20710'>Silhouette Score Method</font>](#ssm)**
      
      5.2.5 - **[<font color='#b20710'>Retrieving the Cluster</font>](#retclus)**
      
             
               
6. **[<font color='#b20710'>Recommendation Systems</font>](#recom)**

      3.1 - **[<font color='#b20710'>Popularity Based Approach</font>](#pop)**     
      
      3.2 - **[<font color='#b20710'>Content Based Recommendation</font>](#content)** 
      
      
7. **[<font color='#b20710'>Conclusion</font>](#conclusion)**

<h4>DATASET FILE LINK : <a href='https://www.kaggle.com/niharika41298/netflix-visualizations-recommendation-eda/?select=netflix_titles.csv'>netflix_titles.csv</a></h4>


<h4>CASE STUDY FILE LINK : <a href='https://github.com/Akshay672/CASE_STUDY_NETFLIX_CLUSTERING_AND_RECOMMENDATION/blob/main/NETFLIX_CLUSTERING_AND_RECOMMENDATION.ipynb'>NETFLIX_CLUSTERING_AND_RECOMMENDATION.ipynb</a></h4>
