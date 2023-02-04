# Multiagent Interactions

An assessment based on Game Theory.

<br>

## Problem Statement
<hr>

Suppose you have a two-player game. Player 1 has two move options, C and B, and Player 2 has two move options, E and D. Player 1's utility/payoff function is:


$$u1(C,E) = 10$$
$$ u1(C, D) = 0 $$
$$ u1(B,E) = 20 $$
$$ u1(B,D) = 10 $$

The utility/payoff function for Player 2 is:


$$ u2(C,E) = 20 $$
$$ u2(C, D) = 10 $$
$$ u2(B,E) = 10 $$
$$ u2(B, D) = 0 $$

<hr>
<br><br><br>


## Subtask 1 : Represent the game as a payoff matrix.

<hr>

A payoff matrix is a table that shows the payoff for each player for each possible combination of moves. The rows of the matrix correspond to the moves of player 1 and the columns correspond to the moves of player 2. The entry in the ith row and jth column of the matrix is the payoff for player 1 when player 1 plays the ith move and player 2 plays the jth move.

<br>

#### Payoff Matrix for Player 1

|   | E  | D  |
|---|----|----|
| C | 10 | 0  |
| B | 20 | 10 |

<br>

#### Payoff Matrix for Player 2

|   | E  | D  |
|---|----|----|
| C | 20 | 10 |
| B | 10 | 0  |

<br>

## Subtask 2 : Provide the dominant strategy for player 1 and justify your answer.
<hr>

A dominant strategy is the one that one player uses to his or her advantage regardless of what other players are doing. A dominant strategy, is one that guarantees a player the biggest reward regardless of what other players perform. Player 1 will most likely play Turn B in this situation. This is due to the fact that regardless of whether player 2 plays turn E or D, it offers player 1 the biggest payoff. The 20 reward is awarded to player 1 if player 2 plays turn E, while the 10 payment is awarded to player 1 if player 2 plays turn D. Thus, playing Turn B is Player 1's dominant strategy.

<br>


|   | E  | D  |
|---|----|----|
| C | 10 | 0  |
| B | 20 | 10 |

<br>




## Subtask 3 : Provide the dominant strategy for player 2 and justify your answer.
<hr>

A dominant strategy is the one that one player uses to his or her advantage regardless of what other players are doing. A dominant strategy, is one that guarantees a player the biggest reward regardless of what other players perform. Player 2 will most likely play Turn E in this situation. This is due to the fact that regardless of whether player 1 plays turn C or B, it offers player 2 the biggest payoff. The 20 reward is awarded to player 2 if player 1 plays turn C, while the 10 payment is awarded to player 2 if player 1 plays turn B. Thus, playing Turn E is Player 2's dominant strategy.

<br>

|   | E  | D  |
|---|----|----|
| C | 20 | 10 |
| B | 10 | 0  |

<br>

## Subtask 4 : Provide the (pure strategy) Nash equilibria (if there are any) and justify.
<hr>

A Nash equilibrium is a state in which no participant is motivated to change their strategy. In other words, a Nash equilibrium is a state in which, given the strategies of the other players, no player can increase their payout by changing their approach. There aren't any pure strategy Nash Equilibria in this situation. If player 1 makes move C, player 2 can make move E and receive a payout of 20, which is greater than the payout of 10 that player 2 would receive if player 1 made move B.

|   | E  | D  |
|---|----|----|
| C |    |    |
| B |    |    |

As you can see, there is no combination of strategies that results in a Nash Equilibrium, as in any combination, at least one player can improve their payoff by changing their strategy.


