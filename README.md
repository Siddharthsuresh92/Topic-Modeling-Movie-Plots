# Topic-Modeling-Movie-Plots

This project was undertaken to generate a topic model based on the text from the movie plot. I wanted to see if a topic model could be developed to identify relationships between movies. 

I built a recommendation system based off of the topic model I developed.

The dataset was originally picked up from: https://www.kaggle.com/jrobischon/wikipedia-movie-plots which has ~35k movies. I filtered and cleaned the dataset and ended up with ~22k movies.

The dataset contains movies from US, Canada, Britain, India (Bollywood) and Australia.

Technical stack:
1. Spacy for the nlp pipeline
2. Gensim (LDA multicore) for generating topic models

The optimal parameters for the model:
1. number of topics = 12
2. passes = 5

To run the project locally, all you need are:
1. Data: Movie-Plots.csv 
2. The topic model: Topic_model.sav
3. Python notebook: Topic Model - Recommendation System.ipynb

The notebook is interactive, so just run all cells and it will prompt for the user input [Note: it takes about 10 mins to initialize the functionalities of the notebook]

If you wish to explore and experiment with these models (or learn), check out the other python notebook, where I did all the exploration.
