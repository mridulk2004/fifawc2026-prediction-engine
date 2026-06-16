# FIFA World Cup 2026 Prediction Engine

A machine learning and Monte Carlo simulation based prediction system for the FIFA World Cup 2026.

## Project Overview

This project predicts FIFA World Cup 2026 outcomes using historical World Cup performance, FIFA rankings, team statistics, and tournament pedigree.

The workflow combines:

* Data Collection & Cleaning
* Feature Engineering
* Random Forest Classification
* Tournament Simulation
* Monte Carlo Forecasting

A total of **10,000 tournament simulations** were run to estimate championship probabilities and likely tournament outcomes.

---

## Key Results

### 🏆 Predicted Champion

**Argentina (12.53%)**

### Top 10 Favorites

| Team        | World Cup Win Probability |
| ----------- | ------------------------- |
| Argentina   | 12.53%                    |
| Brazil      | 11.25%                    |
| France      | 10.21%                    |
| Spain       | 9.28%                     |
| England     | 8.34%                     |
| Germany     | 7.06%                     |
| Netherlands | 4.90%                     |
| Belgium     | 4.45%                     |
| Portugal    | 2.94%                     |
| Uruguay     | 2.93%                     |

### Most Likely Final

**Argentina vs Spain (2.09%)**

---

## Visualizations

### Forecast Dashboard

Data/charts/01_forecast_dashboard_hero.png

### Championship Favorites

Data/charts/02_championship_favorites_ranking.png

### Tournament Progression Analysis

Data/charts/03_tournament_progression_analysis.png

### Power vs Conversion Analysis

Data/charts/04_power_vs_conversion_scatter.png

### Historical Pedigree vs Forecast

Data/charts/05_historical_pedigree_vs_forecast.png

### Most Likely Final Matchups

Data/charts/06_most_likely_final_matchups_arc.png

---

## Methodology

### Data Sources

* FIFA Rankings
* Historical World Cup Results
* Team Performance Statistics
* Tournament Structure Data
* Team Historical Pedigree

### Feature Engineering

Key features include:

* FIFA Ranking
* FIFA Rating Points
* Goals Scored (Last 4 Years)
* Goals Conceded (Last 4 Years)
* Wins, Draws and Losses
* Host Nation Indicators
* World Cup Pedigree Metrics
* Historical Tournament Progression

### Machine Learning Model

**Model:** Random Forest Classifier

**Target Classes:**

* Home Win
* Draw
* Away Win

### Tournament Simulation

The complete FIFA World Cup 2026 format was simulated:

* Group Stage
* Third-Place Qualification Rules
* Round of 32
* Round of 16
* Quarterfinals
* Semifinals
* Third-Place Match
* Final

---

## Monte Carlo Forecasting

* Simulations: **10,000**
* Successful Simulations: **10,000**
* Simulation Errors: **0**
* Matchup Probability Cache: **2,233 Unique Matchups**

The simulation engine estimates:

* Championship Probability
* Final Appearance Probability
* Semifinal Probability
* Quarterfinal Probability
* Most Likely Final Matchups

---

## Repository Structure

```text
├── notebooks/
│   ├── 01_data_audit_and_merge.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_model_training_and_evaluation.ipynb
│   ├── 03_5_2026_team_projection.ipynb
│   └── 04_world_cup_monte_carlo_simulation.ipynb
│
├── data/
│   ├── processed/
│   └── predictions/
│
├── charts/
│
├── models/
│
├── README.md
└── requirements.txt
```

---

## Future Improvements

Planned Version 2 enhancements:

* Current Squad Market Values
* Player Club Form Integration
* Golden Boot Predictions
* Golden Ball Predictions
* Best Young Player Predictions
* Social Media Sentiment Analysis Dashboard
* Live Tournament Updating During FIFA World Cup 2026

---

## Author

**Mridul Kumar**

Production & Industrial Engineering
Delhi Technological University (DTU)

