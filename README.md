# TMDB-Movie-Dataset-Analysis
Analysis on the The Movie Database (TMDb) to generate cutting edge business insight from the dataset distribution. 

# Background
What can we say about the success of a movie before it is released? 
Are there certain companies (Pixar?) that have found a consistent formula? 
Given that major films costing over $100 million to produce can still flop, this question is more important than ever to the industry. 
Film aficionados might have different interests. Can we predict which films will be highly rated, whether or not they are a commercial success?

# About TMDb
[The Movie Database (TMDB)](https://www.themoviedb.org/about) is a community built movie and TV database. 
Every piece of data has been added by an amazing community dating back to 2008. 
TMDb's strong international focus and breadth of data is largely unmatched and something they are incredibly proud of. 
Put simply, TMDB live and breathe community and that's precisely what makes TMDB different.

# Analysis Introduction
Using the Movie Database (TMDB) dataset, analysis will be carried out with the aim of finding the trends that tends to drive the Revenue of a movie. 

To achieve this, the following questions will be answered in the analysis:

- Who are the top movie directors for higher revenue generation?. 
- How does the adjusted revenue correlate with the movie popularity, runtime and average vote
- Which genre of movie leads in generating revenue?
- Who are the top directors in the movie genre with leading revenue generation?
- Which genre is more popular?

To answer the above questions from the Movie Dataset, the following features will be used from the dataset:

- Popularity
- Director
- Runtime
- Genre
- Vote Average 
- Revenue Adjusted 

# Dataset links
- [Raw Dataset on Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- [Pre-cleaned data](https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd1c4c_tmdb-movies/tmdb-movies.csv)

# Files
- investigate and Analysis The Movie Database.ipynb : This file contains the full analysis code and exploratory operations on the dataset

# Conclusions
From the analysis carried out on the Movie database dataset, the follow were discovered:

- Overall, a movie director one may want to look out for to have a movie with high revenue will be among 'Steven Spielberg', 'James Cameron', 'Peter Jackson', 'George Lucas', or 'Robert Zemeckis' as they are the top 5 directors with high cumulative adjusted revenues for movies whose adjusted revenue are above average.

- The popularity, runtime or vote average of a movie does not directly infer the possible revenue of a movie as there is no distinct correlation of these variables against the adjusted revenue.

- Comedy Genre stands out as a very lucrative genre of movie to go into as the cumulative adjusted revenue is high with the genre leading the chart in popularity and vote average.

- The list of directors one should look out for to direct a Comedy only Genre movie with the aim of high revenue generation will be 'Todd Phillips', 'Dennis Dugan', 'Keenen Ivory Wayans', 'Adam McKay', or the combination of 'Bobby Farrelly and Peter Farrelly'

# Limitations
- The cast in a movie play a significant role in the overall general perception of a movie which may impact the revenue generated. However, the cast was not consider to give justification to the revenue by top directors. If the director and specific performing cast members are considered, it will give a different dimension to the list of directors one should look out for to have a movie with high revenue.

- The dataset does not have details about the writers of the movies. The kind of writer for a movie greatly impact the movie output which may also impact the revenue generated.

# Acknowledgments
- Udacity learning community 
- The dataset used in this project was generated from [The Movie Database](https://www.kaggle.com/datasets/tmdb/themoviedb.org) API. This product uses the TMDb API but is not endorsed or certified by TMDb.
Their API also provides access to data on many additional movies, actors and actresses, crew members, and TV shows. You can [try it for yourself here](https://www.themoviedb.org/documentation/api).

# Author
Name : Oguche Victor Ojochenemi

Contact : [linkedin](https://www.linkedin.com/in/victoroguche/) , [twitter](https://twitter.com/VictorOguche6)
