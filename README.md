# 🎬 Emotion-Based Movie Review Recommendation System
![](image.jpg)

This project analyzes **IMDB movie reviews** using **emotion and sentiment detection** techniques to recommend films based on the user's current emotional state. It combines the power of **VADER**, **TextBlob**, and **NRC Lexicon** to extract deeper insights from reviews and recommend movies that align with your mood.







---

## 🌟 What Makes This Project Unique?

Unlike traditional recommendation engines that rely on genres or ratings, this system:
- **Detects dominant emotions** (e.g., joy, sadness, fear) from reviews using **NRC Lexicon**
- **Computes sentiment scores** using **VADER**
- Groups similar emotions (e.g., `happy`, `relaxed`, `excited`) for **flexible, mood-based suggestions**
- Provides **personalized movie recommendations** based on **user input emotion**

---

## 📦 Dataset

- **Source**: `imdb-movies-dataset.csv`
- **Key Columns**:
  - `Title`
  - `Rating`
  - `Review`
  - `Description`

---

## 📌 Features

- Cleaned and preprocessed raw movie reviews
- Detected dominant emotions from each review using `NRCLex`
- Calculated compound sentiment scores using `VADER`
- Visualized rating distribution using `seaborn`
- Provided user-personalized recommendations based on selected emotion

---

## 🛠️ Technologies Used

```python
pandas, numpy, matplotlib, seaborn, sklearn, nltk, vaderSentiment, textblob, nrclex
