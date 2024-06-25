This is a simple implementation of the Tic Tac Toe game in Python. The game allows two players to take turns marking spaces in a 3×3 grid, with the goal of placing three of their marks in a horizontal, vertical, or diagonal row.

Features
1.Two-player mode
2.Simple text-based interface
3.Immediate win condition checking after each move

printBoard(xState, zState)
Prints the current state of the game board.
xState: List of boolean values representing the positions marked by player X.
zState: List of boolean values representing the positions marked by player O.

checkWin(xState, zState)
Checks if there is a winning condition met by either player X or player O.
xState: List of boolean values representing the positions marked by player X.
zState: List of boolean values representing the positions marked by player O.

How to Play
Run the script using a Python interpreter.
Players take turns entering the position number (0-8) where they want to place their mark.
The game will display the updated board after each move.
The game will automatically check for a win condition after each move and declare the winner if found.
Requirements
Python 3.x
