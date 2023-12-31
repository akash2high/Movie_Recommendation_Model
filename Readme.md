## Movie Recommender
## Major Project
- PG-dbda : CDAC ACTS Bengaluru

## Overview

- Developed a [content based movie recommender](https://developers.google.com/machine-learning/recommendation/content-based/basics) that uses Kaggle's THE MOVIES Dataset
- [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
- Deployed over Heroku Cloud
- Uses TMDB-API that fetches the poster path and overview of the movie displayed in the frontend
- Input - Movie Name
- Output - Recommends 10 movies with their similarity score

## Requirements

- [Python](https://www.python.org/downloads/)
- [Pandas](https://pandas.pydata.org/)
- [Streamlit](https://streamlit.io/)
- [Anaconda](https://www.anaconda.com/)
- [Heroku](https://www.heroku.com/)
- [Tmdb](https://www.themoviedb.org/documentation/api)
- [scikit-learn](https://scikit-learn.org/stable/)

## Model Used
- [CountVectorizer](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html)
- [Cosine Similarity](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.pairwise.cosine_similarity.html)

## Methodology

# movie_recommender_V1_preProcessing
- Pre Processing and train data preparation
- exporting train.csv

# recommender_tester
- Run test cases
- Do recommendations

## Snapshot
![alt text](https://github.com/oliabhi/Movie-Recommender/blob/main/Images/heroku.png)


## Project - URL
- [MOVIE RECOMMENDER](https://group11edbda.herokuapp.com/)
- Deployed over Heroku cloud
