# 2048_Puzzle-
The 2048 Puzzle project is a Python implementation of the popular 2048 sliding tile game. This project helps develop skills in GUI programming, matrix manipulation
Grid Setup and Tile Movement:

A 4x4 grid represents the game board, and tiles with values (2, 4, etc.) move up, down, left, or right.
When tiles with the same value collide, they merge into a new tile (e.g., two "2" tiles merge into a "4").
Score Calculation:

Each merge adds the tile’s value to the player’s score, displayed in real-time.
Game Logic:

Tiles spawn in random empty cells after each move, and the player wins by creating a tile with a value of 2048.
If no moves are available, the game is over.
User Interface (UI):

Uses Tkinter for the GUI, displaying the grid, tiles, score, and restart option.
Tile colors change based on value, enhancing visual clarity.
