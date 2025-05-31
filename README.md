# Movie-Recommendation-System

# 🎬 Simple Movie Recommender System

This project is a **content-based movie recommendation system** built using Python and the [MovieLens Dataset](https://grouplens.org/datasets/movielens/). It uses movie metadata such as genres, user tags, and popularity ratings to recommend similar movies. The system performs data preprocessing, text vectorization, and cosine similarity computation for generating high-quality recommendations.

---

## 📦 Features

- Load and preprocess `movies.csv`, `ratings.csv`, `tags.csv`, and `links.csv`.
- Merge and clean genre and tag information.
- Generate popularity labels using average rating and count.
- Use TF-IDF vectorization on metadata (genres + tags + popularity).
- Compute cosine similarity between movies.
- Support fuzzy title matching (e.g. “Dark Nite” → “The Dark Knight”).
- Get top-k recommendations based on similarity.
- Save and load trained models for efficiency.

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/movie-recommender.git
cd movie-recommender
