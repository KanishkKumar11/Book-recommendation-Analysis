# 📚 Book Recommendation Analysis

This project implements a **collaborative filtering-based book recommender system** using **proximity calculations**. It utilizes **cosine similarity** and **k-nearest neighbors (KNN)** to generate personalized book recommendations for users.

## 🚀 Features
- Uses **collaborative filtering** to find similar users.
- **Recommends the top 5 books** for each user.
- Works with **sparse matrix representation** of user-book ratings.
- Saves recommendations in a **CSV file**.

## 📂 Project Files
- `Ratings_final_output.libsvm` - Processed user-book ratings in libSVM format.
- `all_user_recommendations.csv` - Final recommendations for all users.
- `Untitled.ipynb` - Jupyter notebook with implementation.

## 🛠 Installation & Requirements
Ensure you have Python installed along with the required libraries:
```bash
pip install numpy pandas scikit-learn
