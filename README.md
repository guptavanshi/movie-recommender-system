# 🎬A Netflix Recommender System
A Content-Based Recommender System built using **Scikit-learn**, deployed via **Heroku**, and based on the Netflix Movies dataset.
Overview

This project builds a movie recommendation engine that:

- Uses content-based filtering (e.g., genres, keywords).
- Calculates similarity between movies with `CountVectorizer` and `cosine_similarity`.
- Provides simple and fast recommendations without requiring external APIs.
- (Optional) You can extend this project later to include TMDB API or IMDB scraping.


## 🛠️ Installation

**Install required libraries:

bash
pip install numpy pandas scikit-learn

**Running the Recommender
Run the following command to start the recommender system logic:

bash
streamlit run app.py

**How It Works
1.Data Extraction

2.Load movie dataset (CSV file).

3.Data Preprocessing

4.Combine genres, keywords, and other text features.

5.Feature Engineering

6.Vectorize text using CountVectorizer.

7.Model Building

8.Compute cosine similarity matrix.

9.Recommendation

10.Retrieve top similar movies.

#Screenshots

screenshot/movie1.png/movie2.png/movie3.png/movie4.png

✨ Future Plans
.Add web interface (Flask or Django)

.Integrate TMDB or IMDB APIs

.Deploy on Heroku or Render

.Perform sentiment analysis on user reviews

*Author
Vanshika Gupta

🧠 About Me
I am a Computer Science student passionate about Data Science, Machine Learning, and building useful tools to make life easier.

🛠 Skills
*Data Analysis

*Machine Learning

*Python Development

🌟 Acknowledgements
Inspired by many open-source projects and tutorials on building recommender systems.










