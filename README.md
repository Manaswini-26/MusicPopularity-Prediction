# 🎵 Music Popularity Prediction

An intermediate-level Machine Learning project that uses **Random Forest Regression** to forecast the popularity of music tracks based on metadata and audio features.



![Correlation Matrix](correlation_matrix.png)
<img width="640" height="480" alt="correlation_matrix" src="https://github.com/user-attachments/assets/2e922632-21bc-4508-bf6e-9854e4bb8348" />


## 📌 Project Overview
The goal of this project is to provide artists and producers with data-driven insights into what makes a song popular. By analyzing features like energy, valence, and loudness, the model predicts a "Popularity Score" (0-100).

## 📊 Dataset
The dataset contains **227 music tracks** with 22 features including:
- **Metadata:** Track Name, Artist, Album, Release Date.
- **Audio Features:** Danceability, Energy, Key, Loudness, Speechiness, Acousticness, Instrumentalness, Liveness, Valence, Tempo.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Scikit-Learn, Matplotlib, Seaborn
- **Model:** Random Forest Regressor with Hyperparameter Tuning (`GridSearchCV`)

## 📈 Key Findings
1. **Loudness & Danceability:** Show a moderate positive correlation (~0.25 - 0.31) with popularity.
2. **Acousticness:** Has a significant negative impact (-0.43) on a track's likelihood to trend.
3. **Model Performance:** The tuned Random Forest model provided the most stable predictions compared to baseline Linear Regression models.



## 🚀 How to Run
1. Clone the repo:
   ```bash

   git clone [https://github.com/yourusername/music-popularity-prediction.git](https://github.com/Manaswini-26/MusicPopularity-Prediction.git)
