# Tennis Data Analysis Script

## Overview
This Python script analyzes tennis data stored in Parquet files, performs various data processing tasks, and generates insights into tennis matches, players, and tournaments.

## Contact Information
For any inquiries or assistance, please contact Arman Mehmandoost at arman13m99@gmail.com.

## Description
The script performs the following tasks:

1. **Data Preparation**:
   - Loads data from Parquet files (`raw_match_parquet`, `raw_odds_parquet`, etc.).
   - Merges the data into a single DataFrame.
   - Converts timestamps to datetime format.

2. **Data Cleaning**:
   - Fills missing values for columns like `gender`, `match_slug`, `winner_code`, and `start_datetime`.
   - Filters out rows based on match duration and minimum period duration.
   - Handles categorical data like player names, genders, and match slugs.

3. **Statistical Analysis**:
   - Calculates average pro years per player.
   - Identifies the player with the highest number of wins.
   - Determines the longest match recorded in terms of duration.
   - Analyzes match durations and distributions.
   - Investigates sets typically played in tennis matches.
   - Evaluates the success of countries in terms of prize money.

4. **Visualization**:
   - Plots histograms and bar charts to visualize match durations, successful countries, and player attributes.
   - Generates scatter plots to explore correlations between player attributes.

5. **Insights**:
   - Computes average aces and double faults per match.
   - Explores the correlation between player attributes and current ranking.
   - Analyzes the distribution of players turning pro by year.
   - Investigates the distribution of left-handed and right-handed players.

6. **Tournament Analysis**:
   - Examines the distribution of tournament ground types.
   - Determines the most common ground types for tournaments.

7. **Match Analysis**:


