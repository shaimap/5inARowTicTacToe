# 5inARowTicTacToe

BASIC GAME DESCRIPTION:

This game will allow you to play a five-in-a-row tic-tac-toe game with players of different personality types. The object of this game is to attain 5 Xs or 5 Os in a row.

DESCRIPTION OF PLAYER TYPES:

The DumbAI will select its next move according to a predictable pattern. It will choose as its next location the grid square with the lowest possible row number and lowest possible column number, provided the grid square is unoccupied.
The SmartAI operates on strategy and the minimax algorithm in order to determine its next move and optimize its probability of winning.
The RandomAI selects its next move by randomly generating a location within the grid.
The Human player is operated by the user.

INSTRUCTIONS:

Run the program from the main class in the GUI package. A Jframe window will appear. 
Choose Player X from the drop-down menu on the left. Choose Player O from the drop-down menu on the right. Press start to begin the game. Press quit to leave game at any time. The text at the top of the GUI displays the current state of the game (player whose turn it is, draws, wins).

BUGS: 

SmartAI does not complete first 5 in a row (gets 4 in a row) and instead completes second 5 in a row available. (SmartAI makes two 4 in a rows before attempting to win).
