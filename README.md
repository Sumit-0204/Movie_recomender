# 🎬 Movie Recommender System

A content-based movie recommendation system built using Python, Pandas, and Scikit-learn. This project allows users to receive personalized movie suggestions based on the similarity of movie features.

![Movie Banner](https://github.com/Sumit-0204/Movie_recomender/blob/main/banner.PNG?raw=true)

---

## 📌 Features

- 🔍 **Search-based Recommendations** – Enter any movie title and get top similar movies.
- 🧠 **Content-Based Filtering** – Recommendations are based on genres, keywords, cast, crew, and overviews.
- 🛠️ **Vectorization Techniques** – Utilizes `CountVectorizer` to convert text data into meaningful vectors.
- 🎯 **Cosine Similarity** – Computes the similarity between movie vectors for accurate results.
- 🗃️ **Data Preprocessing** – Cleans and combines multiple data columns to enhance model accuracy.

---

## 🗂️ Dataset Used

- **Movies Metadata** from [TMDb](https://www.themoviedb.org/)
- Merged columns include:
  - `genres`
  - `keywords`
  - `cast`
  - `crew` (especially director)
  - `overview`

---

## 🧰 Technologies Used

- Python 🐍  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook

---

## 🚀 How It Works

1. **Data Preprocessing**  
   Combine genres, cast, crew, keywords, and overview into a single feature.

2. **Text Vectorization**  
   Apply `CountVectorizer` to transform text data into numerical format.

3. **Similarity Calculation**  
   Use `cosine_similarity` to compute the closeness between movie vectors.

4. **Recommendation Function**  
   A function that takes a movie title as input and returns top 5–10 similar movies.

---

## 📷 Sample Output

```python
recommend("Avatar")
