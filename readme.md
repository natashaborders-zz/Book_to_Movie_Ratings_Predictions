For this project, I am going to examine films based on novels and use linear regression to predict box office success of a movie based on the source book success.

I will start with web scraping a list from Goodreads:

https://www.goodreads.com/shelf/show/books-made-into-movies
These will provide me with the titles of all the books that have been turned into movies.

I will then explore the book data using Goodreads API, to retrieve the rating on the novel and information about the author (if applicable), and match it to the list above based on the titles of the books, if needed.

Finally, I will use a Kaggle movie information dataset to get the information about the movies I need and append that to the dataset (acquired).

The result will be a dataset where each row will represent a novel made into a movie, and I will use the linear regression to examine the relationship between the movie and the novel it's based on.

This repo contains the work files and the resulting presentation for this project.
