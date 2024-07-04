# Machine Learning Notebooks

This folder contains the Jupyter notebooks that I developed for the Omdena UEFA Euro 2024 Analytics Project. Each notebook addresses a specific aspect of player and team performance analysis using various machine learning techniques and data from current and past UEFA Euro tournaments.

## Notebooks

1. **Top 5 Players Analysis (`top_5_players.ipynb`):**
   - Analyzes the top-performing players in the UEFA Euro tournaments from 2012 to 2024.
   - Identifies the top 5 players in each tournament based on various performance metrics.
   - Utilizes a Random Forest Regressor, optimized through hyperparameter tuning, to predict player ratings.

2. **Home Advantage Influence (`home_advantage_influence1.ipynb`):**
   - Investigates the impact of home advantage on match outcomes in UEFA Euro tournaments.
   - Quantifies the influence of playing at home on team performance and match results using regression models.

3. **Quantifying Team Strengths and Weaknesses (`quantify_teams_kmeans.ipynb`):**
   - Analyzes team strengths and weaknesses by clustering teams based on historical match scores and performance statistics.
   - Uses K-means clustering to group teams and identify patterns and similarities in their playing styles and performance.
  
## Data Source: fbref.com

The data for these notebooks is sourced from fbref.com, a comprehensive and reliable database for football statistics. fbref.com provides detailed player and team statistics, including goals, assists, minutes played, and advanced metrics such as expected goals (xG) and expected assists (xAG). The data is regularly updated and sourced from reputable football leagues and tournaments, making it a trustworthy source for my analysis. Using fbref.com ensures that my analysis is based on accurate and up-to-date information, allowing for meaningful insights and reliable model predictions.
