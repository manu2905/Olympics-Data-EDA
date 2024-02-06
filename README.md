# Olympic Data Analysis SQL Project

**## Overview**

This SQL project analyzes 120 years of Olympic history using two datasets: `athletes` and `athlete_events`. The `athletes` dataset contains information about all players who participated in the Olympics, while the `athlete_events` dataset provides details about all Olympic events over the years. The project aims to answer various queries related to medal counts, player achievements, and Olympic events.

**## Datasets**

The project includes two CSV files:

1. `athletes.csv` - Information about all players participating in the Olympics.
2. `athlete_events.csv` - Details about Olympic events over the years. The "athlete_id" in the `athlete_events` dataset refers to the "id" column in the `athletes` table.

## Problems Solved

The SQL queries in this project address the following problems:

1. Identify the team that has won the maximum gold medals over the years.
  
2. For each team, print the total silver medals and the year in which they won the maximum silver medals.
   
3. Find the player who has won the maximum gold medals among those who have won only gold medals (never won silver or bronze).
  
4. Identify, for each year, the player who has won the maximum gold medals. In case of a tie, print comma-separated player names.
  
5. Determine in which event and year India won its first gold, silver, and bronze medals.

6. Find players who won gold medals in both summer and winter Olympics.
  
7. Identify players who won gold, silver, and bronze medals in a single Olympics. Print player names along with the year.
    
8. Find players who have won gold medals in consecutive three summer Olympics in the same event. Consider only Olympics from 2000 onwards.

## Usage

1. Import the provided CSV files (`athletes.csv` and `athlete_events.csv`) into your SQL Server database.
   
2. Execute the SQL queries provided in the project to analyze the Olympic data.

Feel free to explore and modify the queries based on your specific requirements.

## Contributing

If you'd like to contribute to this project, feel free to submit pull requests or open issues on the GitHub repository.


