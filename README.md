# Steam Game Recommender
 
## Overview
A machine learning project that analyses over 15,000 Steam games to:
- Predict a game's rating score (Regression)
- Classify games as likely hits or flops (Classification)
- Cluster similar games and recommend titles (Unsupervised Learning)
 
## Dataset
Ultimate Games Dataset (https://www.kaggle.com/datasets/rudrakumargupta/ultimate-games-dataset-15k-games-43-features), containing 15000 games and 40+ features.
 
## Methods
1. Data cleaning & feature engineering (see notebooks/01, 02)
2. Regression: Ridge Regression, evaluated with RMSE and R²
3. Classification: Logistic Regression vs. Decision Tree, evaluated with precision/recall
4. Clustering: K-Means with PCA-assisted feature prep, elbow method for k selection
 
## Key Findings
- [e.g. Genre X is the strongest predictor of rating]
- [e.g. Regression achieved R2 of 0.XX]
- [e.g. Classifier achieved XX% precision]
 
## How to Run
```
git clone https://github.com/<username>/steam-game-recommender.git
cd steam-game-recommender
pip install -r requirements.txt
jupyter notebook
```
 
## Next Steps
- Add a Reinforcement-Learning game-playing agent (see companion project)
- Deploy as a small Streamlit demo

