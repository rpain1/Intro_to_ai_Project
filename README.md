Tic-Tac-Toe Game User Documentation
Introduction
This document serves as a comprehensive guide for users of the Tic-Tac-Toe Game, a simple yet engaging game developed using Python's Tkinter library. This game offers a classic Tic-Tac-Toe experience with the added functionality of playing against a computer opponent and tracking game statistics.

Requirements
Python 3.x
Tkinter library (usually included with Python)
Matplotlib library for Python (for visualizing game statistics)
Installation
Ensure Python 3.x is installed on your system.
If Tkinter is not installed, you can install it using your package manager. For example, on Ubuntu, you can use sudo apt-get install python3-tk.
Install Matplotlib using pip: pip install matplotlib.
Starting the Game
To start the game, run the script tic_tac_toe.py. A window will open with the game interface.

Game Features
Play Modes:

Two-player mode: Play against another human player.
Vs. Computer mode: Play against an AI opponent.
Game Controls:

Click on a square to make a move.
Press 'Space' to toggle between playing against another player or the computer.
Press 'R' to restart the game.
Press 'E' to exit the game.
Game Status:

A status bar at the bottom of the window displays whether you are playing against a human or the computer.
Game Statistics:

The game tracks the number of wins for each player and the number of draws.
Visualizations:

At the end of the session, the game can display bar charts and pie charts showing game outcomes and win/draw counts.
Game Rules
The game is played on a 3x3 grid.
Players take turns placing their mark (X or O) in empty squares.
The first player to get 3 of their marks in a row (up, down, across, or diagonally) wins the game.
If all 9 squares are filled without a winner, the game is declared a draw.
Exiting the Game
To exit the game, you can either:

Press the 'E' key.
Close the game window.
Troubleshooting
Game Doesn't Start: Ensure Python and all required libraries are correctly installed.
Display Issues: Make sure your screen resolution is compatible with the game window size.
