# Movies
 Updated Dojo Project

 ### Under Construction

# Overview 
The project uses a movie database to explore what are successful movies? Some of the specific findings reflect impact from the COVID-19 pandemic. 
   - Adventure films generate the most revenue. 
   - Long  films generate more reveue than short films (2000-2001).
   - Films earned more revenue in 2018  than 2020.
   - PG filmes create more revenue (2010 - 2020)

# Data
For this project, I have been requested to extract information from the IMDB (Internet Movie Database) and TMDB (The Movie Database) in order to analyze what makes a movie successful.

#### [Data Dictionary](https://developer.imdb.com/non-commercial-datasets/)
#### [Downloads](https://datasets.imdbws.com/)
#### [Additional  years](https://github.com/coding-dojo-data-science/data-enrichment-linear-regression-with-movies/tree/3669d5b9170c2b16a1371c54c65c80de0324f810/Data/2010-2021)
# Project Stages and Deliverables
1. Preparing Data and creating 3 files (title basics, ratings, and aka). These files are a  great sources  that includes details about revenue, budget, genres, runtime, and titles.
2.  Creating a API yelp data extraction and exploratory data analysis.
  - Create 4 filtered databases initally.
      - Movie-Production-Business-Analysis repository
    - title_basics.csv.gz
    - title_akas.csv.gz
    - title_ratings.csv.gz
3. Combined movie  data file
4.  Prepare movie data base for SQL and created usable tables
     - title_basics
     - title_ratings
     - title_genres
     - genres
     - tmdb_data
5.  Hypothesis Testing and Visuals
     - Does the MPAA rating of a movie affect how much revenue the movie generates?
     - Did 2018 films generate more revenue than 2020?
     - Do movies that are over 2.5 hours have a significantly different revenue than movies that under 1.5 hours in length?
     - Does the genre of a movie affect how much revenue a movie generates?
6.  Extract Data from SQL to Tableau (under construction)
  
# Visual (Seaborn and Tableau)

#### Visual 1: Bar Graph Showing Revenue by Genre (Seaborn)
![alttext](https://github.com/Elispreng/Movies/blob/main/Images/Bar%20Plot%20for%20Revenue%20by%20Genre.png)

This plot shows that adventure films generate the most revenue. 

#### Visual 2: Bar Plot  Showing Revenue by MPAA rating
![image](https://github.com/Elispreng/Movies/blob/main/Images/Bar%20Plot%20for%20Revenue%20by%20Rating.png)

The plot shows that PG  movies earn the most revenue. 

# Summary and Recommendations

Based on the hypothesis testing and visualizations, several key recommnedations and insights are supported.
  - PG movies with a runtime of 150 minutes in the adventure genre earn the most revenue.
  - Films in 2018 earned more revenue than 2020 films during the pandemic. 

### For further information


For any additional questions, please contact **doctor.eemail@gmail.com**
