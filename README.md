# Dice-Battle
Two players face each other in a dice game. The goal is to be the first to reach at least N points. In every turn, the player choose to throw between 1 and D dices (common six-sided dices). The number of points scored is 1 if the result of one of the dices is 1. Otherwise, it's the sum of the dices. We will study two variants of this game :
- sequential variant : the two players play in turn (the first player has then an advantage)
- simultaneous variant : the players play at the same time. If they both reach N points or more, it's the player that exceeds the most N points that wins. If both have exactly N points, they are tied.

The purpose of this project is to determine an optimal game strategy (and to test this strategy against other strategies). If a player wins, his gain is 1. If he lost, his gain is -1. If the game is tied, his gain is 0. It is therefore a zero-sum game.

You can found the code and the statistical tests in the jupyter notebook 'Dice Battle.ipynb'.
