# EPL-Reliability-and-Betting

This project investigates the reliability of pregame betting odds
and player statistics in predicting English Premier League match
outcomes. Historical match data, betting odds, and player statistics
were analyzed to evaluate the accuracy of money line betting odds,
identify potential oversights, and determine the most impactful
player metrics. First, a logistic regression model using only betting
odds achieved an accuracy of 56%, but failed to predict ties. Next, a
Random Forest Classifier trained on all available player statistics
achieved a lower overall accuracy of 47%, but successfully predicted
some ties. To improve performance on player statistics, we iden-
tified and combined the top 5 player statistics from the Random
Forest model and the top 5 statistics using the Pearson Correlation
Coefficient. This refined model achieved 48% accuracy. To further
enhance the player model, new normalized statistics, such as goals
per match, assists per match, shots per match, tackles per match,
and saves per match, were introduced to better capture player
impact on a match to match basis. Players with fewer than five
appearances were excluded because their limited data often skewed
results, as they had minimal opportunity to contribute meaningfully
in matches. After excluding those players with limited appearances
and adding the new statistics, the overall accuracy increased to 51%
when using all player statistics and 53% with only the top metrics.
Although the betting model outperformed player statistics in over-
all accuracy, the latter successfully predicted ties, highlighting a
complementary strength. Combining betting odds and player sta-
tistics in future models could improve predictive performance. This
analysis provides actionable insights for bookmakers, bettors, and
club management, and lays a foundation for further research.