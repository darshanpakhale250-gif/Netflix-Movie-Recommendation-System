# 🎬 Netflix Recommendation System

This project builds a **movie recommendation system** using the Netflix dataset.  
It applies **Collaborative Filtering** with the **SVD algorithm** from the `surprise` library to predict user ratings and recommend movies.

---

## 📊 Features
- Data cleaning and preprocessing of Netflix user–movie ratings
- Filtering users and movies based on minimum rating activity
- Applying SVD model for recommendation
- Evaluation using cross-validation (RMSE)
- Personalized movie recommendations for a sample user

---

## 🧠 Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Surprise  

---

## 🧩 Dataset
- `combined_data_1.txt.zip` → Contains customer ratings for Netflix movies  
- `movie_titles.csv` → Contains movie names and release years  

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/Netflix-Recommendation-System.git
cd Netflix-Recommendation-System
pip install -r requirements.txt
