# connect-4-ai

This is a HTML5 implementation of Connect 4 with an AI opponent.

The AI algorithm uses the negamax algorithm which is a variation version of the Minimax algorithm. It also uses alpha-beta pruning the reduce the search space.

Future moves are searched upto a depth of 6.

Moves are ranked based on using a heuristic value. Winning states that require the fewest number of moves are given the highest value and losing states are given a low value. States that are neither winning or losing are evaulated based on the number of possible winning lines of the player minus that of the opponent. Moves that lead the the highest score are selected.