# Tic-Tac-Toe
Overview
->This is a simple command-line Tic-Tac-Toe game implemented in C++. The game allows two players to play against each other by entering their moves on a 3x3 grid. The program ensures valid moves, checks for a winner after each turn, and announces the result at the end of the game.

Features
1.Two-player mode
2.Input validation to prevent duplicate or invalid moves
3.Dynamic game board updates
4.Automatic winner detection
5.Displays the final game result (Win or Draw)

How to Play
1.Run the program in a C++-compatible environment.
2.Enter the names of Player 1 and Player 2.
3.Players take turns to enter a number (1-9) corresponding to the grid position.
4.The board updates after each move.
5.The game ends when a player wins or the board is full (draw).

Board Position Mapping
 1 | 2 | 3
-----------
 4 | 5 | 6
-----------
 7 | 8 | 9

 Compile:
  g++ -o tic_tac_toe tic_tac_toe.cpp

File Structure
- tic_tac_toe.cpp  # Main game logic
- README.md        # Project documentation
  
