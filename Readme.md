This was part of a competition submission for the Wharton Data Science Competition. The goal of this competition was to predict NCAA women march madness tournament wins for the first 10 matches. Additionally, the second task was to rank teams in each region. 

In order to rank the teams, I wrote an elo-rating system, based off of the chess.com elo-ranking system. 

For prediction wins, I modified the game data to be historical statistics before each game. So each column would be the average statistics of that team before that certain game. This is to prevent any bias since if the model knows the statistics from the game that it is predicting, then it wouldn't be an accurate way to predict the win. 

This makes since you wouldn't know the stats of that certain game when you attempt to predict who wins. 

By using different accuracy measurements, I tested a couple models such as random forest, logistic regression, and neural networks with different parameters.

Ultimately this project has solidified my knowledge on data analysis and modification. 