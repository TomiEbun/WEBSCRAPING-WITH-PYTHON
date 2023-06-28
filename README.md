# WEBSCRAPING-WITH-PYTHON-IMBD Movie Data-Analysis
The Internet Movie Database (IMDb) is a huge informational resource that offers details on a huge number of movies as well as their ratings, Meta score, gross, year of release, votes, movie duration, movie genre, movie directors and stars. The Internet Movie Database has become a major player in the world of the film industry study and appreciation. IMDb's rating system, which allows viewers to assign a score to movies from 1 to 10, is one of the distinguishing characteristics of the website. 
IMDb data analysis provides underlying trends and attributes that contribute to movie success stories, revealing audience preferences, critical reactions to movies and social trends that have shaped the film industry. In this project, I conducted a data-driven inquiry into the world of movie success stories using the capacity of IMDb data research.
Moving forward to the main aim of this project, I will be analyzing the top 250 movies in the internet movie database to gather insights.


### Dataset Overview
The dataset that was used for this analysis was web scrapped from the IMBD website; a popular online platform that was established in 1990. It serves as the most comprehensive movie database in the world, offering information about movies, TV episodes, and celebrities to professionals, movie fans worldwide, enthusiasts and researchers allowing them to explore their favorite shows and stay updated with the latest releases. The platform also keeps users informed about upcoming movies, trailers, industry news, and events. It offers user engagement features that allow users to make lists of their favorite movies, keep track of their viewing history, and join in discussion boards to share their views and ideas with other movie fans. The Top 250 selected IMBD ranging between 1978 to 2019 were analyzed. 


### Gathering (Scrapping) the data
The python request library with its methods was used to get the data from the IMDB URL(https://www.imdb.com/search/title/?count=250&groups=top_1000&sort=user_rating) and the content of the URL is parsed via Beautiful Soup. Matplotlib and seaborn libraries were imported for visualization purposes. For loop function was used to extract the content of the URL, and then returned it as a Pandas data frame using the panda’s library.


## Data Columns Description:
The dataset consists of top 250 IMBD movies(rows) with 11 columns in total.
Movie Title: refers to the name of the movies and it serves as a unique identifier for each movie entry in the dataset.
Year of Release: This is the specific year in which each movie was released to the public.
Movie Rating: This attribute represents the rating of the movie by the public.
Movie Duration: This provides information about the length of each movie.
Movie Genre: This represents the genre to which each movie (e.g., "Action," "Drama,", "Crime" etc.).
Movie Votes: This refers to the number of votes received by the movie, and it may indicate the level of audience engagement or popularity of the movie.
Movie Description: This refers to a summary of the movie's plot or storyline.
Movie Directors: This are the names of the individuals responsible for directing the movie.
Movie Stars: This are the names of the prominent cast members in the movie (lead actors/actresses)
Gross: This represents the gross revenue or earnings generated by the movie.
Meta Score category: This represents the categorization of the movie's Meta score.

### CONCLUSION:
The insights from this project will help in understanding audience preferences, analyzing the popularity of different genres and identifying trends in the movie industry and to evaluate movies for critical reception, quality, and rating distribution for comparisons.
