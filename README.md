# 🎌 Anime Recommendation System using Cosine Similarity

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/ML-Recommendation%20System-green)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

Content-based anime recommendation system using TF-IDF and cosine similarity with rating-based weighting and similarity optimization.

---

## 📌 Project Overview

This project builds a **content-based recommendation system** for anime using:

- TF-IDF Vectorization
- Cosine Similarity
- Rating-based feature weighting

The system recommends anime similar to a given title based on genre and rating patterns.

---

## 🎯 Objective

To design an intelligent recommendation engine that suggests similar anime based on content similarity using **cosine similarity**.

---

## 📂 Dataset Description

The dataset contains information about anime, including:

- Anime ID
- Name (title)
- Genre
- Type (TV, Movie, OVA, etc.)
- Number of episodes
- Rating
- Number of community members

---

## 🔍 Data Preprocessing

Steps performed:

- Removed missing values in key columns (`name`, `genre`)
- Handled missing values in `type` and `episodes`
- Converted categorical and textual data
- Reset index and cleaned dataset

---

## 🧠 Feature Engineering

### 🎯 Genre-Based Features
- Used **TF-IDF Vectorizer** to convert genres into numerical vectors

### ⭐ Rating-Based Features
- Normalized rating values
- Combined with TF-IDF vectors to improve recommendation quality

---

## 📊 Cosine Similarity

Cosine similarity measures how similar two anime are based on feature vectors.

- Values range from **0 to 1**
- Higher value = more similar

---

## ⚙️ Recommendation System

### 🔧 Functionality

- Input: Anime name
- Output: Top N similar anime

### Example:

recommend_anime("Mushishi", num_recommendations=5)

Output:
List of recommended anime with:
* Name
* Genre
* Type
* Rating

---

## 🚀 Advanced Enhancement

⭐ Weighted Recommendation

- Combined genre similarity with normalized ratings
- Improved recommendation accuracy

---

## 📈 Key Learnings

* Building recommendation systems from scratch
* Working with text data using TF-IDF
* Understanding cosine similarity
* Feature engineering for better recommendations
* Difference between content-based and collaborative filtering

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* TF-IDF Vectorizer
* Cosine Similarity

---

## ▶️ How to Run

git clone https://github.com/your-username/anime-recommendation-system-cosine-similarity.git
pip install -r requirements.txt

# Run notebook
jupyter notebook

---

## 📌 Future Improvements

- Add user-based collaborative filtering
- Build hybrid recommendation system
- Deploy using Streamlit
- Add search UI

---

## 👩‍💻 Author

Meghana C Varghese
Data Scientist | Machine Learning Enthusiast
