# Main NBA Champion predicting notebook

- Loads and cleans NBA team and playoff data for analysis
- Builds a power ranking of playoff teams using the SRS metric
- Uses K-Means clustering to group playoff teams by statistical similarity
- Visualizes clusters and principal components to interpret team strengths
- Trains an XGBoost model to predict playoff game outcomes based on SRS, offensive, and defensive ratings
- Evaluates model accuracy and bias using test data and classification metrics
- Implements functions to predict matchup probabilities and simulate playoff series
- Runs Monte Carlo simulations to estimate each team's probability of winning the NBA Finals

# Feature engineering Game_stats notebook

- Loads and cleans NBA game-level data
- Examines the data using summary statistics, corelation heatmap, and k-means clustering
- Uses logistic regression to predict the winner of a basketball game based on the game stats in that game
- Shows which in game stats that have the greatest impact on win/loss

# What we still need to do
- Link the game stats notebook in the main notebook in the relevant place and in a way that doesn't require a reader to run either notebook before viewing
- Write a summary and conslusions at the end of the main notebook that highlights our findings
