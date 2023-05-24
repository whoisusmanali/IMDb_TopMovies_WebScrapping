# IMDb_TopMovies_WebScrapping
In this project I use IMDb website to get all the detail about
movies like the name, release date and rating. I use Python for this purpose and use Request, Beautiful Soup and Pandas libraries for extraction of the data. The final results shows the Top 250 movies that are all time famous and with good rating.


## Libraries/Dependencies used:
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

# Screenshots:
![image](https://user-images.githubusercontent.com/104086680/235835271-ef29956e-263f-4f20-963f-6a56b38e40b7.png)

![image](https://user-images.githubusercontent.com/104086680/235835408-f3c3ec2d-ecd4-434b-a274-c71ac90a8b9d.png)

## Website:
![image](https://user-images.githubusercontent.com/104086680/235835545-93fe60e6-1eb1-4b5c-bb7a-c7acf2e50b14.png)

![image](https://user-images.githubusercontent.com/104086680/235835613-d1a94263-cc1f-478f-9ae3-4dcc5b581b2d.png)




