# DSI-Movie-Recommendation-System---NSDC-Data-Science-Projects
# Movie Recommendation System Using SVD
## This project implements a collaborative filtering-based movie recommendation system using Singular Value Decomposition (SVD). It was developed as part of a Columbia University Data Science Institute program and uses the MovieLens 100k dataset.

# Overview
## The goal of this project is to predict user ratings for movies and generate personalized recommendations. The MovieLens 100k dataset contains 100,000 ratings from 943 users on 1,682 movies.

# Dataset
## Source: MovieLens 100k

## Contains user IDs, movie IDs, ratings (1–5), and timestamps

# Methodology
## Used the SVD algorithm from the surprise library to perform matrix factorization

## Tuned hyperparameters such as the number of latent factors and number of epochs

## Evaluated performance using Root Mean Square Error (RMSE)

# Results
## Best RMSE achieved: [insert value, e.g., 0.91]

## Model performed well in predicting ratings based on latent features

# How to Run
## 1. Open the Jupyter/Colab notebook

## 2. Install dependencies (e.g., scikit-surprise) if needed

## 3. Run the cells in order

# Future Improvements
## Add content-based or hybrid filtering

## Explore alternative algorithms (e.g., KNN-based models, NMF)

##Integrate movie metadata (genres, release year, etc.)
