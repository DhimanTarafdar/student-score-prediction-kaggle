# Student Exam Score Prediction

This repository contains my solution for the **Kaggle Playground Series - Season 5, Episode 1**. The goal is to predict exam scores based on various student-related features.

## Highlights
- **Final Score (RMSE):** 8.74213 on Kaggle Leaderboard.
- **Model:** Tuned XGBoost Regressor with 5-fold Cross-Validation.
- **Key Techniques:** - Advanced Feature Engineering (`total_effort`, `study_efficiency`).
  - Robust Scaling and Pipeline integration.
  - Comprehensive EDA and Correlation Analysis.

## Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Pipelines, ColumnTransformer)
- XGBoost

## Results
The model is highly stable with minimal overfitting (Difference between Train and Val RMSE is < 0.05).
