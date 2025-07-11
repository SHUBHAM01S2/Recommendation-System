
# 🎬 Movie Recommendation System

A content-based movie recommendation system built using Python and machine learning. It suggests similar movies based on the movie selected by the user, using NLP techniques on movie metadata.

---

## 📌 Project Overview

This project uses the TMDB 5000 movies dataset to build a recommendation engine. It processes movie metadata like cast, genres, overview, director, and keywords to compute similarity between movies and recommend the top similar ones.

---

## 📁 Repository Structure

```
recommendation-system/
│
├── movie_tag.pickle              # Processed movie feature vectors
├── similarity.pickle             # Cosine similarity matrix (excluded via .gitignore)
├── recommendation_system.ipynb   # Main notebook for recommendation system
├── tmdb_5000_movies.csv          # Movie metadata dataset
├── tmdb_5000_credits.csv         # Cast and crew dataset
├── .gitignore                    # Ignores large and unnecessary files
```

---

## 🔍 Key Features

* Content-based filtering using movie metadata
* Text preprocessing using NLP (lemmatization, vectorization)
* Cosine similarity to find similar movies
* Pickled files for fast recommendation loading
* Clean and modular Jupyter notebook for analysis and modeling

---

## 🧪 How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/SHUBHAM01S2/Movie-Recommendation-System.git
   cd Movie-Recommendation-System
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook:**
   Open `recommendation_system.ipynb` in Jupyter Notebook or VS Code and follow the instructions to test the recommender.

---

## 🧠 Algorithms & Techniques

* Natural Language Processing (NLP)
* CountVectorizer
* Cosine Similarity
* Pickle for serialization
* Pandas & NumPy for data manipulation

---

## 📊 Dataset

* [TMDB 5000 Movies Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)


## 🛠 Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* NLTK
* Jupyter Notebook
* Pickle

---

## 📬 Contact

**Shubham Sharma**
📧 [shubhamshar98050@gmail.com](mailto:shubhamshar98050@gmail.com)

---

