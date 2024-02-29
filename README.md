# MovieLensRecSys_IT492_GRP1
A Collaborative Filtering Recommendation System on the MovieLens 20M dataset.

# MovieLens Dataset for Collaborative Recommendation System

## Introduction

- This dataset contains ratings and movie information from MovieLens, a movie recommendation service.
- It includes 20,000,263 ratings and 27,278 movies.
- These ratings were provided by 138,493 users.
- The data spans from January 09, 1995, to March 31, 2015.
- The dataset was generated on October 17, 2016.

## Content

The dataset is provided in six files:

1. `rating.csv`: Ratings of movies by users.
    - Columns: userId, movieId, rating.

2. `movie.csv`: Movie information.
    - Columns: movieId, title, genres.

3. `link.csv`: Identifiers to link to other sources.
    - Columns: movieId, imdbId, tmdbId.

4. `genome_scores.csv`: Movie-tag relevance data.
    - Columns: movieId, tagId, relevance.

5. `genome_tags.csv`: Tag descriptions.
    - Columns: tagId, tag.

6. `tag.csv`: Tags applied to movies by users.
    - Columns: userId, movieId, tag, timestamp.

## Usage

- This dataset is suitable for building and evaluating collaborative recommendation systems.
- The main files of interest are `rating.csv` and `movie.csv`, which contain user ratings and movie information, respectively.
- You can use this data to develop recommendation algorithms based on user preferences and movie attributes.

## Acknowledgements

The original datasets were provided by MovieLens. Please cite the following paper if you use this dataset in your research:

F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4, Article 19 (December 2015), 19 pages. DOI=http://dx.doi.org/10.1145/2827872

## Inspiration

Here are some ideas worth exploring using this dataset:
- Which genres receive the highest ratings? How does this change over time?
- Determine the temporal trends in the genres of movies released.

## Note

This repository does not include timestamp data and tagging activity data.

