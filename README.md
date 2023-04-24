# IMDb_TopMovies_WebScrapping
In this project I use IMDb website to get all the detail about movies like the name, release date and rating. I use Python for this purpose and use Request, Beautiful Soup and Pandas libraries for extraction of the data. The final results shows the Top 250 movies that are all time famous and with good rating.


## Libraries used:
1. Beautiful soup
2. request
3. pandas


## Steps involved:
1. Import the above mentioned libraries.
2. Get the url of the IMDb of top 200 movies.
3. Use Request library to get the response from the website.
4. The data received were not clear to read so parse the data to get the classes and div of the webiste.
5. Now use the findall function with "a" link to extract the name of the movie.
6. Did some data cleaning to extract the only name of the movie.
7. After this extract the year of the movie released by using findall with class name of the year.
8. The third step is to extract the rating of the movie with class name.
9. Performed some data cleaning steps to get the rating of the movie.
10. Store all the data into dictionary.
11. Store the dictionary into pandas dataframe.
12. Now save the data into .cvs format.


