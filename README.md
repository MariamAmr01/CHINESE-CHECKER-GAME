# CHINESE-CHECKER-GAME
The game is implemented in JAVA with GUI using AlphaBeta algorithm. 

## Heuristic Function
The whole idea of the heuristic function used is to calculate how far both of them from one of the possible places of the goal depending on the calculated index. 
If differnce between aiSum and playerSum negative, it's good for the player. Otherwise it's good for AI. 

## GUI
Game starts with the player choosing which color to play with then choosing from the 3 difficulty modes (Hard [depth:5]) - Medium([depth:3]) - Easy([depth:1])).
Player choosen color is in the bottom of the window.
AI color is automatically set the other color and it is on the opposite side of the player (top).
Player chooses certain node to move and click on an empty place to move the node to this place. 
Choosen node is colored green till the player ends his turn.
Possible moves: moves to adjacent empty places or hopping.
When the player chooses invalid move (hops in wrong place or choosing inadjacent place) a window appears to alert the player that it's an invalid move.
When the player chooses to hop a window appears to ask if the player wants to hop again, if not it ends the player's turn and the AI makes it's move.
When all nodes of the player reach their goal a screen appears showing that he won.
When the computer wins a screen appears showing that the computer won.
When the players click 'ok' on the winning screen the window closes as there are no more possible moves.
