# Phase_1_Project-Microsoft-Movie-Studio-Recommendations
<h1 style="text-align: center;"> Microsoft Movie Studios Recommendations </h1>

<img style="display: block;
            margin-left: auto;
            margin-right: auto;
            width: 50%;"
     src="images/projector_img.jpg" />

#### Author: Tahron Herring


### Overview

<hr>

<p style="text-align: left;"> 
The technology giant, Microsoft is looking to expand it's lines of business by jumping into the movie business.  This project will analyze data from various movie tracking and rating companies to help them determine how to best direct project investments that help ensure a successful start to this venture. 
</p>

### Business Understanding

<img src="images/reels_img.jpg"
     width=750
     height=150
     />

<hr>

<p style="text-align: left;"> 
Like every successful business Microsoft wants to make the best decisions that they can with the resources that they decide to dedicate to a particular new venture. With this in mind, we want to analyze the peformance of past and current films in order to guide what areas Microsoft should make it's initial movie investments. 
</p>

<p style="text-align: left;"> 
A good way of determining which films have performed the best at the box office is to look at two important metrics, a films popularity and a films profitability.  It may be suprising to many but measuring these two incators are not exactly straight forward. For the purposes of this project we will be using data from five different datasources to help us determine which film categories are the most popular and which are the most profitable.    
</p>   

### Data Understanding

<img src="images/movie_theater_1.jpg"
     width=500
     height=150
     />

<hr>

<p style="text-align: left;">
  
To assess film popularity and film profitability we will examine five seperate datasources. The datasets will come from Box Office Mojo, IMDB, Rotten Tomatoes, The Movie DB, and The Numbers. Based on the contents of the datasets popularity will be determined from the data housed in the IMDB, The Movie DB, and the Rotten Tomatoes datasources. These sources contain features like rating, popularity, genre, vote_count, etc. Profitability will be determined from the Box Office Mojo and The Numbers datasources. These sources contain features like domestic_gross and production_budget, etc.  
    
</p>    

### Data Analysis

#### Popularity: The Movie Database Insights

#### Popularity: IMDB Insights

#### Popularity: Rotten Tomatoes Insights

#### Profitability: Box Office Mojo Insights

#### Profitability: The Numbers Insights


#### Genre Analysis
<p style="text-align: left;">
The last step in our analysis process is to analyze the top genre results that we recieved from each of the datasources.  There are many different ways we could go about this, however the method that we have chosen to follow is to perform a word(genre) frequency breakdown.  The process will consist of breaking up the genre groups into the individual genres.  Once we have the individual genres, they will be counted and the genre with the highest frequency will be what we recommend. For example, if a movie is classified as a Action, Adventure, Sci-Fi film then each word(Action, Adventure, Sci-Fi) would get its count incresed by 1 as we continued through the other movie selections. 
</p> 


### Conclusions

<hr>

<p style="text-align: left;">
Based on the analysis performed there are three recommendation for Microsoft Movie Studios:
</p> 

<p style="text-align: left;">
<b>Focus on producing Action Films -</b> In our genre ranking system Action ranked highest in popularity and came in second for profitability. This is a good balance and should allow the studio to create a popular film that produces great returns.
</p>

<p style="text-align: left;">
<b>Focus on producing Adventure Films -</b> For the Adventure genre it ranked second in popularity and first in profitability.  Akin to the Action genre, Adventure should produce nice results for Microsoft as it achives good balance.
</p>

<p style="text-align: left;">
<b>Focus on producing Sci-Fi Films -</b> The Sci-Fi genre ranked 4th and 3rd in popularity and profitablility. While these films didn't come in as high as the other two it still achived a nice balance for the two metrics.
</p>

### Next Steps

<hr>

<p style="text-align: left;">
The analysis of this data could have been done a number of different ways that all may have provided value for Microsoft. The next round of analysis may want to focus on the follow goals to improve the quality of the results.
</p> 

<p style="text-align: left;">
<b>Increase the top sample size for analysis -</b> In our effort to analyze the data we only looked at the top 5 results from each datasource. Looking at larger sample of the top performing movies would expand the genre list that is created and therefore it may change the scores/rankings of the genres.
</p>

<p style="text-align: left;">
<b>Use different analysis methods -</b> We limited the scope of our work to look at the popularity and profitability of the films from the datasources.  There are other metrics that can be studied to help determine where Microsoft should focus the resources of their movie studio as they launch.
</p>

<p style="text-align: left;">
<b>Expand the datasources used -</b> For the purposes of this project we looked at five differnt datasources.  However, if there were more sources used for this project there may be value added to the results of the analysis.
</p>