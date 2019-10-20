# WeekendMovieTrip
This project uses a K-means Clustering Model, along with data sets containing movie titles, genres, user ratings, and user tags, to determine similar movies to recommend using the other ratings and tags of movies by other users.

### About the Data
The data set included 4 different files of different data: movies.csv, ratings.csv, tags.csv, links.csv. The links.csv file was not used in this analysis.
###### movies.csv
- movieId - the numeric id of the movie
- title - the title of the movie, including the year of the movie to differentiate between remakes
- genres - a pipe-separated string of genres (may have 0 or more genres per movie )
######  ratings.csv
- userId - the numeric id of the user who rated the movie
- movieId - the id of the movie that is being rated
- rating - the user rating of the movie
- timestamp - the timestamp when the movie was rated by the user
###### tags.csv
- userId - the numeric id of the user who tagged the movie
- movieId - the id of the movie that is being tagged
- tag - the user tag (string) of the movie
- timestamp - the timestamp when the movie was tagged by the user

### Data Source
https://grouplens.org/datasets/movielens/

The data set selected from this website was ml-latest-small.zip

### Troubleshooting GitHub Notebook Rendering
Sometimes GitHub has trouble rendering notebooks. Should GitHub have troubles rendering the notebook in this project, please navigate to https://nbviewer.jupyter.org/ and enter https://github.com/nlaluzerne/WeekendMovieTrip in the text bar to view the notebook.
