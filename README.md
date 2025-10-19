# Visualization of Chess Game Data

## Membrers
- Jibril Gueye
- Daniele Buondonno
- Emanuele Calo

## Project Overview

The goal is to explore patterns related to player ratings, game outcomes, openings, and match durations through visualizations.
The project is implemented in Python using various libraries for data manipulation and plotting.

---

## Dataset

The dataset `games.csv` contains information on chess matches, including:
- Player ratings
- Game outcomes (win, loss, draw)
- Opening codes (ECO)
- Victory conditions
- Number of turns

---

## Analyses Included

The analysis covers:

- **Game Turns Histogram** – distribution of the number of turns per match, with outliers removed  
- **Average Ratings Histogram** – distribution of player ratings, ignoring default rating values  
- **Rated vs Unrated Games** – proportion of rated games in the dataset  
- **Victory Status Countplot** – shows the reason for game termination (checkmate, timeout, resignation, draw)  
- **Opening ECO Analysis** – percentage of wins, losses, and draws for different opening codes  
- **Rating Difference by Game Outcome** – boxplots showing rating differences between players grouped by result (win, loss, draw)

These analyses use descriptive statistics and visual exploration to uncover patterns in chess matches.
