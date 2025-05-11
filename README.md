# 🍽️ Recipe Recommender System using KNN

## 📌 Project Overview
This is a machine learning-based recipe recommender system that suggests recipes based on ingredients provided by the user. It uses the **K-Nearest Neighbors (KNN)** algorithm to find and recommend similar recipes from a dataset.

## 🎯 Objective
To help users discover recipes that match the ingredients they have, promoting convenience and reducing food waste.

## 🧰 Tools & Technologies
- **Python**
- **Pandas, NumPy** – Data manipulation
- **Scikit-learn** – KNN algorithm
- **NLTK / spaCy** – Text preprocessing (optional)

## 📊 Dataset
- A CSV file containing:
  - `Recipe Name`
  - `Ingredients`
  - `Cuisine`
  - `Cooking Time`
  - `Difficulty`
- Preprocessed to remove missing values and standardize ingredient names

## 🧠 ML Workflow
1. Clean and tokenize ingredient text
2. Vectorize the ingredients using `TfidfVectorizer` or `CountVectorizer`
3. Use K-Nearest Neighbors to find similar recipes
4. Return top `k` recommended recipes based on cosine similarity

## 💡 Features
- User enters ingredients (e.g., "rice, onion, garlic")
- System recommends the most relevant recipes
- Option to filter by cuisine or cooking time

