NBA Player Value Analysis
Author: Christien Bryan Reyes Viray


This project analyzes the value of NBA players based on their performance stats and salary during the 2022-2023 season. Using Python and Excel, I explored metrics like Player Efficiency Rating (PER), games played, minutes played, and PER per million dollars to determine which players gives the most value to their teams.


Summary
- Cleaned and analyzed NBA data using Python.
- Created visualizations and a summary table in Python and Excel.
- Key metric: PER per million (how efficient a player is relative to their salary).
- Top value players identified: Austin Reaves and Desmond Bane.


Files Included
- 'main.ipynb': Python script with cleaning, filtering, and visualizations.
- 'nba_valuablePlayers_summaryTable.xlsx': Excel file with summary table and visualization.
- 'cleaned_pergame_and_advance_2023_w_salaries.csv': Original dataset from: https://www.kaggle.com/datasets/albarpambagio/nba-player-stats-and-salaries-2014-2023?resource=download
- 'nba_valuablePlayers_cleaned.csv': File exported from Python after cleaning, filtering, and visualizations
- 'visuals': folder containing visualizations from Excel and Python


Libraries Used
- pandas
- matplotlib.pyplot
- seaborn


Visuals
- Summary Chart: visuals/Excel Visuals
- Python Charts: visuals/Python Visuals


Key Findings and Notes
- To ensure a fair and meaningful comparison of value, the analysis was scoped to regular season statistics and applied 2 key filters:
    - Minutes Played: Only players averaging more than 24 minutes per game were included to focus on core rotational players whose contributions are essential and consistent
    - Adjusted Salary: Only players with an adjusted salary greater than $1 million were included to filter out reserve players on minimum contracts whose high PER-to-salary ratio could skew results
- The results came down to the top 7 most valuable players being Alpren Sengun, Desmond Bane, Tyrese Maxey, Immanuel Quickley, Tre Jones, KJ Martin, and Austin Reaves.
- Austin Reaves and Desmond Bane emerged as the two most valuable players based on performance-to-salary efficiency
- Reaves respresented the peak of cost-efficienct as he was the lowest-paid player out of the top 7. He delivered near league average PER around 15, offering exceptional value and significant potential.
- Bane represented high performance at a reasonable cost. While Bane had a higher salary than Reaves, he delivered elite level PER of around 18, providing star quality production without a top tier salary.
 - Other players either offered lower PERs based on their adjusted salaries while others offered exceptional PERs but their salaries were just too high.
 - In summary, Austin Reaves and Desmond Bane are the most valuable players for their teams relative to their salaries. Austin Reaves would be the better option for teams who want a high potential player for a lower cost. Desmond Bane would be the better option for teams who want elite level perofrmance at a non-max salary.



