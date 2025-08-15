Here’s a rewritten, more polished, and well-structured version of your project description:

---

# **Movie Recommender System with Sentiment Analysis**

**Motto:** *"Unlock Your Cinematic Journey!"*

## **Overview**

This repository contains a **comprehensive movie recommender system** that combines **personalized content-based recommendations** with **sentiment analysis** of movie reviews. Built using **state-of-the-art machine learning techniques**, the system helps users discover movies that match their tastes while also providing insights into audience opinions.

By leveraging **movie metadata**, **natural language processing (NLP)**, and **API integration**, the system ensures that users not only get recommendations but also enjoy a **richer, more informed movie-watching experience**.

Dataset: [TMDB Movie Metadata – Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

---

## **Features**

### **1. Personalized Movie Recommendations**

* Users enter the name of a movie they like.
* The system finds **similar movies** using a **precomputed cosine similarity matrix**.
* Recommendations are purely **content-based**, focusing on metadata such as genres, keywords, and descriptions.

### **2. Movie Details Fetching**

* Integrates with the **TMDb API** to retrieve:

  * Movie posters
  * IMDb IDs
  * Additional metadata (release date, overview, ratings, etc.)

### **3. Sentiment Analysis of Reviews**

* IMDb reviews are **scraped** using **BeautifulSoup**.
* A **pre-trained sentiment analysis model** classifies each review as **"Good"** or **"Bad"**.
* Users can explore both the **recommendations** and **public sentiment** before deciding what to watch.

---

## **Web Application Interface**

Built using **Flask**, the application offers an intuitive, user-friendly interface with the following pages:

1. **Homepage** – Overview of the system and how it works.
2. **Recommend Page** – Input a movie title and get personalized recommendations.
3. **Reviews Page** – Browse reviews and sentiment analysis results for any recommended movie.

---

## **Data & Models**

The project includes:

* **Dataset**: `dataset.csv` – Contains movie metadata.
* **Precomputed Models**:

  * `similarity.pkl` – Cosine similarity matrix for recommendations.
  * `npl_vectorizer.pkl` – NLP vectorizer for text processing.
  * `reviews_model.pkl` – Sentiment classification model.

---

## **Technology Stack & Dependencies**

* **Python** – Core programming language.
* **Flask** – Web framework for the application.
* **NumPy** – Numerical computations.
* **Pandas** – Data manipulation and analysis.
* **scikit-learn** – Machine learning tools for vectorization & similarity computation.
* **BeautifulSoup** – Web scraping IMDb reviews.
* **html5lib** – HTML parser for BeautifulSoup.
* **Pickle** – Load/save serialized models.

---

## **Performance Evaluation**

User satisfaction is a top priority. The system’s effectiveness is evaluated through:

* **User Feedback** – Ratings, reviews, surveys.
* **Engagement Metrics** – Retention rate, interaction frequency.
* **Offline Evaluation** – Simulated recommendations tested against historical preferences.
* **A/B Testing** – Comparing different algorithms by randomly assigning user groups.

These methods help refine the recommendation engine and improve the overall user experience.

---

## **Goal**

The ultimate aim is to **enhance the joy of movie discovery**—saving users time, matching their tastes, and providing deeper insights into what others think of a movie. This way, users embark on a **cinematic journey like never before**.

---


