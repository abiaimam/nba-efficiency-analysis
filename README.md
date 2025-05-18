# nba-efficiency-analysis
Analyzing NBA player efficiency using excel and python
Dataset link:
The dataset is too large to upload directly here, so you can download and view it from OneDrive:
https://waynestateprod-my.sharepoint.com/:x:/g/personal/ho9797_wayne_edu/EUl8IScNrNZJmojxnBvJ8uwBBMwby0dh_HTPhCGv-C33aA?e=sqJXQi

# NBA Player Efficiency Analysis

## Project Overview
- Cleaned the dataset to exclude players with fewer than 20 games played.
- Calculated efficiency scores using the basic NBA Effiency formula, which aims to provide simple metric for evaluating a players overall impact: ((Points + Rebounds + Assists + Steals + Blocks) - (Mised Field Goals + Missed Free Throws + Turnovers))/Games Played
- Visualized the top 20 players by efficiency and compared efficiency to points scored.

## Key Findings
- There is a strong positive correlation (0.87) between efficiency and points scored, indicating players who score more tend to have higher efficiency ratings. This can be confirmed because players who scoree more points contribute mor heavily, impacting the effiency score.

## How to View the Project
- Open the NBAproject.ipynb in Jupyter Notebook to see the full code and interactive plots.
- The dataset is available here: https://waynestateprod-my.sharepoint.com/:x:/r/personal/ho9797_wayne_edu/Documents/nba_efficiency.csv?d=w27217c49ac0d49d69a88f19c1bc9f2ec&csf=1&web=1&e=ZzxNqj

## Interpretation
- The horizontal bar chart showed the top 20 NBA players by efficiency score, with the highest being Joel Embiid
- The scatterplot that shows the top ten Nba players for efficiency vs points shows that since points are a heavy part of the efficiency formula, the more points a player has, the more likely the efficiency is higher. However, for players like Joel Embiid who had the highest efficiency, the scatterplot reveals he had very low points compared to the rest of the players, due reasons like missing a significant portion of the season due to injury.
- The linear regresson model showing a correlation of 0.87 indicates that while points scored are highly correlated with player efficiency, efficiency also weighs other aspects like rebounds, assists, and steals. This makes it a more comprehensive measure of a player's overall impact.

---
Feel free to explore the notebook and reach out if you have questions!
