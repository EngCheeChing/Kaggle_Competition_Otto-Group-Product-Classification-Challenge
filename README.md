# Kaggle_Competition_Otto-Group-Product-Classification-Challenge
Private Leaderboard Score Rank:  409 / 3511 Teams


A 3 layers stacking architecture of ensemble technique had deployed for the challenge.

1st Level: Train KNN, RF, XGBoost, NN models with various transformation data and utilize these models predictions as meta-features, also there are engineering features generated by t-SNE, K-Means Clustering algorithms.

2nd Level: Train Neural Network & XGBoost model by using meta features and engineering features that generated from 1st Level.

3rd Level: This final layer is composed by a weighted mean from 2nd Level predictions.
