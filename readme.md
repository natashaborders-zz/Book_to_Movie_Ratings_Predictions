For this project, I am going to examine films based on British and American novels and use linear regression to predict box office success of a movie based on the source book success.

I will start with webscraping two lists from Wikipedia:

https://en.wikipedia.org/wiki/Category:Films_based_on_British_novels
https://en.wikipedia.org/wiki/Category:Films_based_on_American_novels
These will provide me with the titles of all the movies in my dataset (approximately 3,204 + 1,703 total)

I will then collect the book data using Goodreads API, to retrieve the rating on the novel and information about the author (if applicable), and match it to the list above based on the titles of the books.

Finally, I will use a Kaggle IMDb movie information dataset to get the information about the movies I need and append that to the dataset.

The result will be a dataset where each row will represent a novel made into a movie, and I will use the linear regression to examine the relationship between the movie and the novel it's based on.

This repo contains the work files and the resulting presentation for this project.
