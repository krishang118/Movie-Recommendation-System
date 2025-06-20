# Movie Recommendation System

This is a content-based movie recommendation system built using Python and the [MovieLens Dataset](https://grouplens.org/datasets/movielens/32m/). 

It analyses movie metadata such as genres, user tags, and popularity ratings to recommend similar movies. The system performs data preprocessing, TF-IDF vectorization, and cosine similarity computation for generating high-quality recommendations.

---

## Features

- Loads and preprocesses the available data files: `movies.csv`, `ratings.csv`, `tags.csv`, and `links.csv`.
- Merges and cleans genre and tag information.
- Generates popularity labels using average rating and count.
- Uses TF-IDF vectorization on metadata (genres + tags + popularity).
- Computes cosine similarity between the movies.
- Supports fuzzy title matching with typo tolerance (e.g. “Dark Nite” → “The Dark Knight”).
- Gets top-k recommendations based on similarity.
  
---

## Prerequisites

```bash
pip install pandas numpy scikit-learn
```

## Installation

1. Download and extract the required MovieLens Dataset on your local machine.
2. Clone this repository on your local machine, and run the Jupyter Notebook file.

---

## Contributing

Contributions are welcome!

---

## License

Distributed under the MIT License.  

