# movie-recommendation-tfidf-logistic-regression
Machine Learning movie recommendation system using TF-IDF text features and Logistic Regression to predict user movie preferences and recommend similar movies.


# Movie Recommendation System (TF-IDF + Logistic Regression)

This project is a **Machine Learning based Movie Recommendation System** that predicts whether a user will like a movie based on movie keywords and text features.

The system uses **TF-IDF vectorization** to convert movie text data into numerical features and **Logistic Regression** to predict the probability that a user will like a movie.

Movies are then **ranked by probability**, allowing the system to recommend the most relevant movies.

---

## Project Goal

The goal of this project is to demonstrate how **Natural Language Processing (NLP)** and **Machine Learning** can be used to build a simple recommendation engine.

The model learns patterns from movie keywords and predicts which movies a user is likely to enjoy.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Jupyter Notebook

---

## Dataset

The dataset contains approximately **4000 movies** with information such as:

- Movie title
- Keywords
- Overview
- Genres

Keywords are extracted and cleaned before being used in the model.

---

## Project Workflow

### 1. Data Loading
Movie dataset is loaded using Pandas.
