# Tic-Tac-Toe-VS-computer
This is a Tic Tac Toe (Player VS Computer) terminal based game built in python.
The game starts with displaying a grid according to which the player has to make his/her next move.
Even though computer moves are random,they are designed in such a way that if you are closer to a winning position, it will make a clever move to block your winning position.  
For example:  
  
  1  |  2  |  3 
-----------------
  4  |  5  |  6
-----------------
  7  |  8  |  9 
-----------------  
If you have made your move at 1 and 3, then the computer will mark its move at 2 so that your winning condition is not fulfilled.  
If any winning condition is met by the player, then a message will be displayed as "You Win!!".  
If any winning condition is met by the computer, then a message will be displayed as "Computer Wins!!".  
If no winning condition is met and the borad is full, then a message will be displayed as "Game Tie!!!".  
