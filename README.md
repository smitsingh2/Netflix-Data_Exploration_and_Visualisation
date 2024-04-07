# Netflix-Data_Exploration_and_Visualisation

● Netflix is one of the most popular media and video streaming platforms. They have over 8000 movies or tv shows available on their platform, as of mid-2021, they have over 200M Subscribers globally. 

● The particular business case focuses on the Netflix show data and provides insightful information on 8807 shows 

● Analyzing the data and generating insights helps Netflix decide which type of shows/movies to produce and how to grow the business
______________________________________________________________________________
## The data is available in a single csv file : 
● Show ID : The ID of the show
● Type: Identifier - A Movie or TV Show
● Title: Title of the Movie / Tv Show
● Director: Director of the Movie
● Cast: Actors involved in the movie/show
● Country: Country where the movie/show was produced
● Date_added: Date it was added on Netflix
● Release_year: Actual Release year of the movie/show
● Rating: TV Rating of the movie/show
● Duration: Total Duration - in minutes or number of seasons
● Listed_in: Genre
● Description: The summary description
______________________________________________________________________________
1. Un-nesting the columns
a. Un-nest the columns those have cells with multiple comma separated values by 
creating multiple rows
2. Handling null values
a. For categorical variables with null values, update those rows as 
unknown_column_name.
b. Replace with 0 for continuous variables having null values. 
______________________________________________________________________________
1. Find the counts of each categorical variable both using graphical and nongraphical analysis.
a. For Non-graphical Analysis:
b. For graphical analysis: 
______________________________________________________________________________
2. Comparison of tv shows vs. movies.
a. Find the number of movies produced in each country and pick the top 10 
countries.
b. Find the number of Tv-Shows produced in each country and pick the top 10 
countries.
______________________________________________________________________________
3. What is the best time to launch a TV show?
a. Find which is the best week to release the Tv-show or the movie. Do the analysis 
separately for Tv-shows and Movies
b. Find which is the best month to release the Tv-show or the movie. Do the 
analysis separately for Tv-shows and Movies
______________________________________________________________________________
4. Analysis of actors/directors of different types of shows/movies.
a. Identify the top 10 directors who have appeared in most movies or TV shows.
b. Identify the top 10 directors who have appeared in most movies or TV shows.
______________________________________________________________________________
5. Which genre movies are more popular or produced more
______________________________________________________________________________
6. Find After how many days the movie will be added to Netflix after the release of 
the movie (you can consider the recent past data)
