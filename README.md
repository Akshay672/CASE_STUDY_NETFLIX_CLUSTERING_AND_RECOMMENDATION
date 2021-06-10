# NETFLIX CLUSTERING AND RECOMMENDATION

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

<b>Show_id </b>                             = Indicating the ID's of Different TV Shows or Movies<br><br>
<b>Type</b>                                 = Indicates whether the recommended show is TV Show or Movie<br><br>
<b>Title</b>                                = Names of different TV Shows and Movies<br><br>
<b>Director</b>                             = Directors of respective TV Shows and Movies<br><br>
<b>Cast</b>                                 = Actors Featured in respective TV Shows and Movies<br><br>
<b>Country</b>                              = Country of Origin of Movie Make<br><br>
<b>Date_Added</b>                           = The Date on which that particular Movie or TV Show was added<br><br>
<b>Release_Year</b>                         = The year in which respective TV Show or Movie Released<br><br>
<b>Rating</b>                               = Recommended on the basis of different Parental Guidance<br><br>
<b>Duration</b>                             = Running of TV Show (in termms of Episodes) or Movie (in minutes)<br><br>
<b>Genre</b>                                = Classification or Type of TV Show or Movie fall under<br><br>
<b>IMDB Weighted Average Vote</b>           = Average Weighted Votes taken from IMDB<br><br>
<b>IMDB Total Votes</b>                     = Collective Votes taken from IMDB<br><br>
<b>IMDB US Voters Rating</b>                = Voters Rating on the basis of US users<br><br>
<b>IMDB Non US Voters Rating</b>        = Voters Rating on the basis of non-US users<br><br>
<b>Reviews from users</b>               = Count of Reviews from Users<br><br>
<b>Reviews from critics</b>             = Count of Reviews from Critics



  ## Task Completed: Table of Content

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


<h4>CASE STUDY FILE LINK : <a href='https://github.com/Akshay672/CASE_STUDY_NETFLIX_CLUSTERING_AND_RECOMMENDATION/blob/main/NETFLIX_CLUSTERING_AND_RECOMMENDATION.ipynb'>NETFLIX_CLUSTERING_AND_RECOMMENDATION.ipynb</a></h4>
