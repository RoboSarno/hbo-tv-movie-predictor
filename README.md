# Problem Statement

> Deciding if a show is going to succeed or not is always a question an execuative wants to know.  
> For a company like HBO they tend to be very selective in what they greenlight.  
> The objective of this project is to understand if a newly proposed show is going to perform well and
> fit the "seal of approval" of a successful HBO show. I am to build a regression (or nerual network) model
> to predict the performance of the show imdb score, tmdb score, tmdb popularity.

LINK

- https://www.kaggle.com/datasets/victorsoeiro/hbo-max-tv-shows-and-movies?select=titles.csv regression problem
- https://www.kaggle.com/datasets/victorsoeiro/amazon-prime-tv-shows-and-movies?select=titles.csv
- https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies?select=titles.csv

# Data Dictionary:

**Model_data**

| Data Name            | Data Description                             |
| -------------------- | -------------------------------------------- |
| person_id            | The Actor ID on JustWatch.                   |
| role                 | Actor or Director                            |
| title                | The name of the movie title                  |
| type                 | TV show or movie                             |
| description          | A brief description of the movie             |
| release_year         | The release year of the movie/show           |
| runtime              | The length of the episode (SHOW) or movie    |
| genres               | A list of genres                             |
| production_countries | A list of countries that produced the title. |
| seasons              | Number of seasons if it's a SHOW.            |

# Conclusion

> My model greatly beat the baseline model. The baselines performance had a percent of variance present in the data that it predicted was -0.0022 while the root_mean_squared_error was 191.56. Where my percent of variance present in the data that my final model predicted was .987 and had a root_mean_squared_error of 21.89. In sum the model was good at finding the linear realtionship between HBO Movie/TVShows and IMDB_Score based on a specific set of features my model will help HBO determine if their next show is going to be a hit.
