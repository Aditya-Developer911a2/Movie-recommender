# 🎬 Movie Recommendation System

A Content-Based Movie Recommendation System built using Python, Pandas, and Scikit-learn. The application recommends movies similar to a selected movie by analyzing metadata such as genres, keywords, cast, and crew.

## Features

* Recommend 5 similar movies based on user selection
* Content-based filtering approach
* Interactive web interface using Streamlit
* Fast recommendation generation using precomputed similarity scores

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Pickle

## Project Structure

```
Movie-Recommender-System/
│
├── app.py
├── movie_dict.pkl
├── Movie_recommender.ipynb
├── requirements.txt
└── README.md
```

## How It Works

1. Movie metadata is preprocessed and cleaned.
2. Important features such as genres, keywords, cast, and crew are combined into a single text representation.
3. Text data is converted into vectors using NLP techniques.
4. Cosine similarity is calculated between movies.
5. The similarity matrix is stored and used to generate recommendations instantly.

## Usage

1. Select a movie from the dropdown menu.
2. Click the **Recommend** button.
3. View the top 5 recommended movies.

## Future Improvements

* Display movie posters using the TMDB API
* Add movie ratings and release dates
* Improve recommendation quality using hybrid filtering
* Deploy the application online using Streamlit Cloud

## Dataset

TMDB 5000 Movies Dataset

## Author

Aditya Kumar Singh

B.Tech Information Technology, RGIPT
