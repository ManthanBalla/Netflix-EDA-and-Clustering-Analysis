# 📊 Netflix EDA & Clustering Analysis

This project explores and analyzes Netflix's content dataset through **Exploratory Data Analysis (EDA)** and applies **Clustering techniques** to uncover hidden patterns and group similar shows/movies.

---

## 📌 Project Overview
Netflix hosts a vast library of movies and TV shows from different countries, genres, and years.  
This project aims to:
- Understand data distribution across content types, release years, and genres.
- Analyze content duration and ratings.
- Identify clusters of similar titles using **K-Means clustering**.

---

## 📂 Dataset
- **Source**: Netflix Titles Dataset (Kaggle)
- **Features Used**:
  - `type` — Movie or TV Show
  - `release_year` — Year of release
  - `rating` — Content rating (e.g., TV-MA, PG, R)
  - `duration` — Duration in minutes or seasons

---

## 🛠 Technologies Used
- **Python**
- **pandas** — Data cleaning & manipulation
- **numpy** — Numerical computations
- **matplotlib** & **seaborn** — Data visualization
- **scikit-learn** — Label Encoding, Scaling, and Clustering

---

## 📊 Exploratory Data Analysis
Performed analysis on:
- Content type distribution (Movies vs TV Shows)
- Release year trends
- Most popular ratings
- Duration trends
- Country-wise content distribution

**Sample visualizations:**
- Bar charts & count plots for content type and ratings
- Line plots for release year trends
- Pair plots for feature relationships

---

## 🤖 Clustering Analysis
- **Preprocessing**:
  - Extracted numeric duration
  - Label encoding categorical variables
  - Standardization using `StandardScaler`
- **Algorithm**: K-Means Clustering
- **Purpose**: Group similar shows/movies based on features like type, release year, rating, and duration.
- **Evaluation**: Elbow Method to determine the optimal number of clusters.

---
