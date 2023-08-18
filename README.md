# FFPredictionModel
using web scraped data to predict 2023 fantasy football scoring

Scoring is in PPR (point per reception), with 6-point rushing/receiving TDs, 4-point passing TDs, 1 point per 10 all-purpose yards, and 1 point per 25 passing yards

Fumbles and interceptions are -2 points

All raw player data scraped off of Pro Football Reference. 

Data was pulled for each player by using a weighted average of the player's statistics from the previous two seasons, with the most recent season weighting double the season before.

The following metrics/statistics were pulled for prediction:

For quarterbacks - Age, QBR, Pass Attempts, Pass Completions, Pass Yards, Pass TDs, Interceptions, Rush Attempts, Rush Yards, Rush TDs, Fumbles, Experience

For running backs and pass-catchers - Age, Targets, Receptions, Receiving Yards, Receiving TDs, Catch Percentage, Rush Attempts, Rush Yards, Rush TDs, Fumbles, Experience

The following team statistics were pulled for prediction - Points Scored Per Game, Points Allowed Per Game, Yards Gained Per Game, Passing Play Percentage

Rookies are not included in projections.
