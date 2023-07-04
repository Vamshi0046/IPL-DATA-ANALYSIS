# IPL Matches Dataset Analysis

This code performs analysis on the IPL (Indian Premier League) matches dataset. It includes various operations such as handling missing values, data visualization, and extracting insights from the dataset.

## Requirements

To run this code, you need to have the following libraries installed:

- numpy
- pandas
- matplotlib

## Instructions

1. Import the required libraries:
   
   - numpy
   - pandas
   - matplotlib.pyplot

2. Load the IPL matches dataset:
   
   - The dataset file should be named "matches - matches.csv".

3. Check for missing values in the dataset:
   
   - If any missing values are found, they can be dropped using the `dropna()` function or filled using the `fillna()` function.

4. Explore the dataset:

   - Get the first five records using `df.head()`.
   - Check the number of rows and columns in the dataset using `df.shape`.
   - Get the frequency of the "player_of_match" column using `df['player_of_match'].value_counts()`.
   - Get the frequency of the "result" column using `df['result'].value_counts()`.
   - Get the number of toss wins for each team using `df['toss_winner'].value_counts()`.

5. Perform data visualization:

   - Create a bar plot for the top 5 players with the most "man of the match" awards.
   - Create a histogram for the number of wins after batting first.
   - Create a bar plot for the top 3 teams with the most wins after batting first.
   - Create a pie plot for the frequency of wins after batting first.
   - Create a histogram for the frequency of wins with respect to the number of wickets.
   - Create a bar plot for the top 3 teams with the most wins after batting second.
   - Create a bar plot for the number of matches played each season.
   - Create a bar plot for the number of matches played in each city.

6. Further analysis:

   - Find the runs scored by a batsman against each team using the "runs_scored" function.
   - Merge two datasets using the "merge" function.
   - Get the top 5 batsmen with the highest runs scored.
   - Create a pie plot for the teams' choices after winning the toss.

## Conclusion

This code provides insights into the IPL matches dataset by analyzing various aspects such as player performance, team performance, and match statistics.

Feel free to modify and adapt the code as needed.

