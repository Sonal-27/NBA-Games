# NBA Games
## Introduction
This project explores the National Basketball Association (NBA) dataset, providing valuable insights into NBA games.
## Background
The dataset, sourced from FiveThirtyEight, is named "nba_dataset.csv" and includes features such as date, season, playoff status, team information, ratings (Elo, CARMELO, RAPTOR), and game-specific metrics.
## Methodology
### Environment Setup
- Utilized Jetstream with Ubuntu 22.04 for cloud computing needs.
- Created an instance named "sonal-project-i535" with m3.large configuration and Web Desktop enabled.
### Data Processing
- Used PySpark for data cleaning and exploration
- Implemented a data lifecycle process.
### Data Extraction
- Downloaded the NBA dataset using PySpark and the following command:
- - wget https://projects.fivethirtyeight.com/nba-model/nba_elo_latest.csv -O nba_dataset.csv

## Results
The NBA Games Analysis project yielded insightful results through a comprehensive exploration of the dataset. Visualizations, including bar charts depicting total matches per team and scatter plots showcasing average scores, provided a clear overview of team participation and offensive performance. Elo ratings over time were effectively illustrated through line plots, enabling the identification of performance trends and trajectories for both Team 1 and Team 2. The list of teams with higher average Elo ratings offered a ranked perspective on consistent strong performers. The linear regression model's predictions, detailed in a table and visualized in a line plot, demonstrated its accuracy in estimating score differences, validated by metrics like MSE, RMSE, and MAE. This project not only addressed specific queries about NBA teams but also showcased a holistic approach to data science, incorporating skills from diverse modules. Teams like Boston (BOS) and Memphis (MEM) emerged as consistently strong performers, validating the Elo rating system. Despite encountered challenges, the project exemplifies the practical application of a varied skill set in the dynamic domain of sports analytics.

## Discussion
The analysis reveals insights into team performances, Elo ratings, and the predictive linear regression model. Challenges include data quality, model complexity, and adapting to NBA dynamics.

## Conclusion
This project demonstrates a holistic data science approach, integrating skills from various course modules. Despite challenges, the analysis showcases the practical application of a varied skill set in the dynamic realm of sports analytics.

## References
https://github.com/fivethirtyeight/data/tree/master/nba-forecasts 

