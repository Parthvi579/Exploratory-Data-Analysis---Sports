# IPL Data Analysis and Visualization

## Project Overview

This project involves performing an Exploratory Data Analysis (EDA) on the Indian Premier League (IPL) dataset. The analysis aims to uncover insights about the most successful teams, players, and the factors contributing to a team's win or loss. Additionally, the project suggests teams or players that companies might consider endorsing for their products.

## Dataset

The datasets used in this analysis can be downloaded from [here](https://bit.ly/34SRn3b). The project involves two primary datasets:

1. `deliveries.csv` - Contains ball-by-ball data of IPL matches.
2. `matches.csv` - Contains match-level data of IPL matches.

## Analysis and Visualizations

The project includes several visualizations to illustrate the findings from the dataset. Below are the key analyses performed:

### Data Loading and Preprocessing

- Loaded the datasets `deliveries.csv` and `matches.csv`.
- Dropped rows with any missing values in `matches.csv`.
- Converted the date column to datetime format in `matches.csv`.

### Descriptive Statistics

- Generated descriptive statistics for both datasets to understand the distribution and summary of data.

### Visualizations

1. **Distribution of Runs Scored in Each Over**
   - **Histogram**: Shows the frequency distribution of runs scored in each over.

2. **Number of Matches Won by Each Team**
   - **Bar Chart**: Visualizes the number of matches won by each team.

3. **Matches Played in Each City**
   - **Bar Chart**: Shows the number of matches played in each city.

4. **Top Players Based on Player of the Match Awards**
   - **Lollipop chart**: Highlights the top players based on the number of Player of the Match awards.

5. **Win by run vs win by wickets**
   - **Histogram plot**: Displays comparison between team win by run and win by wickets.

6. **Analyze the performance of top players**
   - **Horizontal bar plot**: displays top players performance analysis

7. **Win Percentage by Team**
   - **Pie Chart**: Displays the win percentage for each team.

## Key Insights

- The distribution of runs scored in each over varies, with some overs being more crucial in determining the match outcome.
- Teams like Mumbai Indians and Chennai Super Kings have a higher number of wins.
- Cities like Mumbai and Kolkata host a significant number of matches.
- Players such as AB de Villiers and Chris Gayle frequently win Player of the Match awards.
- The win percentage highlights teams with consistent performance.

## Conclusion

The EDA of the IPL dataset provides valuable insights into the dynamics of the league. By leveraging this analysis, stakeholders can make informed decisions regarding team strategies, player endorsements, and match preparations.

## Repository Structure

- `deliveries.csv`: Contains ball-by-ball data of IPL matches.
- `matches.csv`: Contains match-level data of IPL matches.
- `Indian Premier League.ipynb`: Jupyter notebook with the complete analysis and visualizations.
- `README.md`: This file.

## How to Run

1. Clone this repository.
2. Ensure you have Python and Jupyter Notebook installed.
3. Install necessary libraries using:
   ```bash
   pip install pandas matplotlib seaborn
