# A spatio-temporal travel in the universe of music


# THE SECOND MILESTONE IS ACCESSIBLE WITH LOADED MAP AT THIS ADDRESS :
[html notebook](http://138.68.129.61/ada/project)

# Abstract
How did music evolve through time and space ? We want to find influencers both in terms of individuals and countries that would shape the music worldmap, and what people listen to.  
We will use the [Million songs dataset](https://labrosa.ee.columbia.edu/millionsong/).  
We listen to a lot of music every day, but perhaps we forget that music has been shaped by history. Maybe there was a battle of influences between genres that has evolved through time ?  
What country has succeeded in influencing the others ? Who were the influencers ? These are just some of the many questions that we ask ourselves. We will answer these questions and many others by providing a interactive map to visualize many aspects of music around the world through time (proeminent genres per country, evolution of loudness, danceability around the world...). We will also study other aspects of music such as the kind of topics sung around the world and how they evolved through time.  
This analysis aims to cast a new eye on the evolution of music through time and space.  



# Research questions

What is the evolution of genre and main influencers ?  
Is there a main genre by country throughout the time ?  
How music disperses and travels?  
Do people like to dance and move to the beat more than before?  
How topics are changing and spreading throughout the years?   
Is there a meaningful change in loudness and tempo over the years?   

# Dataset

We use the [Million songs dataset](https://labrosa.ee.columbia.edu/millionsong/).  
Especially, we want to use the artist name, tags, localization, danceability, energy, loundness, tempo.

We want to use the familiarity to detect influencers.

There is a lot of annotations that come with this dataset such as the tagtraum dataset (genre) and musiXmatch (lyrics), which we will use to enrich the dataset.

We expect to have more data on the US than for the rest of the world and that could be a problem for a world scale study, but there still is some data for a lot of countries and we can put a focus on the propagation inside the US.
In order to strenghten this analysis, we plotted the distribution of the artist-countries for only 1% of the data chosen randomly.


![alt text](https://github.com/ben2034/ada-private/blob/master/pace/musics%20per%20countries%20(subset).png)


This confirms the previous hypothesis.


# A list of internal milestones up until project milestone 2

Fetch and clean the million songs dataset.  
Exploratory analysis of dataset and visualize the distribution of data.
Discuss and support the completion of our research questions.   
Construction of a detailed pipeline.  
Have some insights in the correlation of different parameters such as tempo with danceability.  

# Questions for TAa
Given that the data is mainly focussing on the usa, should we restrict our analysis to the USA or would it still be relevant to use this dataset for the entire world? Should we scrape more data from other countries..?
