# ICC-Champions-Trophy-1998-2025-Analysis

# ICC Champions Trophy Cricket Data Analysis

This project analyzes the ICC Champions Trophy Cricket Dataset from 1998 to 2025. It explores various aspects of the tournament, including match results, player information, and team performance.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
- [Data Analysis and Visualization](#data-analysis-and-visualization)
    - [Match Statistics](#match-statistics)
    - [Team Performance](#team-performance)
    - [Player Analysis](#player-analysis)
    - [Temporal Trends](#temporal-trends)
    - [Correlation and Outliers](#correlation-and-outliers)
    - [Clustering Teams](#clustering-teams)
- [Conclusion](#conclusion)

## Introduction

The ICC Champions Trophy is a prestigious cricket tournament. This project aims to gain insights from the historical data to understand team performance, player contributions, and trends over time.

## Dataset

The project uses two datasets:
- **`all_champions_trophy_matches_results.csv`**: Contains match-level data like dates, venues, teams, scores, and winners.
- **`all_champions_trophy_players_list.csv`**: Contains player information like team, role, and experience.

## Data Cleaning and Preprocessing

The code performs the following data cleaning steps:

- Handles missing values in both datasets using mean/mode imputation.
- Converts the 'Date' column to datetime format for easier analysis.

## Data Analysis and Visualization

### Match Statistics

- Analyzes the total number of matches played.
- Examines the distribution of wins per team.
- Visualizes the distribution of match margins.

### Team Performance

- Calculates and visualizes the win distribution for each team.
- Identifies the top venues for matches.

### Player Analysis

- Explores the distribution of players across teams.
- Analyzes the distribution of player roles.
- Relates team composition (number of players) to overall performance.

### Temporal Trends

- Examines the temporal trends of matches played per year.
- Visualizes the number of matches played over time.

### Correlation and Outliers

- Calculates the correlation between numerical features.
- Identifies potential outliers using box plots.

### Clustering Teams

- Groups teams based on their performance using K-means clustering.
- Visualizes the clusters to identify high and low-performing teams.

## Conclusion

This project provides a comprehensive analysis of the ICC Champions Trophy dataset. The findings can be useful for understanding historical trends, predicting future outcomes, and optimizing team strategies.

If you found my work insightful then fork and star my repository.

Thankyou!! 
