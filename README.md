# Movie-Recommendation-System-Project
![Movie recommendations!](https://images.app.goo.gl/QUP8K11karnunNnY9)

## Overview
This project aims to develop a recommendation system for movies using the MovieLens dataset. The system leverages collaborative filtering, content-based filtering, and hybrid approaches to provide personalized movie recommendations to users based on their past ratings and preferences.

## Table of Contents
- [Overview](#overview)
- [Data](#data)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Building Models](#building-models)
- [Evaluation](#evaluation)
- [Conclusion and Recommendations](#conclusion-and-recommendations)

## Data
- [MovieLens](https://grouplens.org/datasets/movielens/latest/) : Contains the MovieLens dataset.
- This dataset was obtained from the GroupLens research lab at the University of Minnesota.

## Data Preprocessing
The dataset is preprocessed to handle duplicates, missing values, and format the data for modeling.

## Exploratory Data Analysis
Exploratory data analysis is conducted to understand user behavior, movie characteristics, and distribution of ratings.

## Building Models
### Collaborative Filtering
- Implemented k-Nearest Neighbors algorithm for collaborative filtering.
- Utilized Surprise library for model development and evaluation.
- Explored various similarity metrics and hyperparameters to optimize model performance.

### Content-Based Filtering
- Leveraged movie metadata (genres) to develop content-based filtering.
- Utilized TF-IDF vectorization and cosine similarity for content-based recommendations.
- Addressed the cold-start problem by recommending popular movies for new users.

### Hybrid Approach
- Combined collaborative filtering and content-based filtering for improved recommendation accuracy.
- Developed a hybrid recommendation system that adapts to user preferences and item characteristics.

## Evaluation
- Evaluated model performance using metrics such as RMSE and MAE for collaborative filtering.
- Utilized cross-validation and grid search for hyperparameter tuning.
- Analyzed the strengths and limitations of each recommendation technique.

## Conclusion and Recommendations
### Conclusion


### Recommendations


