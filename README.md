# Movie Recommender System (Collaborative Filtering)

This project uses collaborative filtering to build a basic recommender system using movie rating data.

---

## 📁 Dataset

Two files:
- `ratings.csv`: User ratings for movies
- `movies.csv`: Metadata (title, genres)

---

## 📊 Approach

- Merge ratings and metadata
- Compute average rating and number of ratings per movie
- Visualize distributions
- Create a utility matrix (userId vs movie titles)
- Use Pearson correlation to find movies similar to a target (e.g., *xXx (2002)*)

---

## 📈 Visualizations

- Histogram of number of ratings
- Histogram of average ratings
- Joint distribution of count vs average
- Heatmap of feature correlations

---

## 📦 Project Structure
    movie-recommender/
    ├── data/
    │   ├── ratings.csv
    │   └── movies.csv
    ├── notebooks/
    │   └── movie_recommender.ipynb
    ├── README.md
    ├── requirements.txt
    └── .gitignore

---

## 🚀 How to Run

1. Clone the repo  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
 3. Run the notebook :
    jupyter notebook notebooks/movie_recommender.ipynb
