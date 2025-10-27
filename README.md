# Tic-Tac-Toe Terminal: A Simple Python Game

A terminal-based Tic-Tac-Toe game written in Python that supports both single-player (player vs AI) and multiplayer (two human players) modes. This project is designed to be a simple, dependency-free script, perfect for learning basic game logic and AI implementation. The code is easy to understand, extend, and experiment with, making it an excellent starting point for beginner Python developers.

Features
Single-Player Mode: Play against a basic AI that makes valid moves.
Multiplayer Mode: Play with another person on the same machine, taking turns on a shared board.
Terminal Input: Make moves by entering numbers corresponding to board positions (1–9).
Simple AI: The AI chooses valid moves at random, providing a basic but enjoyable single-player experience.
No External Dependencies: The game works out of the box with Python 3.x, with no need for additional libraries.
Small, Readable Code: The code is concise and easy to understand, allowing for quick modifications and experimentation.
Clean Game Logic: Designed with simplicity in mind, making it an ideal project for learning about game loops, condition checking, and AI basics.
Requirements
Python 3.6+
A terminal or command prompt to run the script.
Quickstart — Run the Game
Clone or download the repository to your local machine.

# Clone Project
Open a terminal and navigate to the project folder.

# bash
cd tic-tac-toe-terminal
Run the game by executing the Python script:

# bash
python TikTacToe.py
At the prompt, choose a mode:

Enter 1 for single player , 2 for multiplayer : 1
computer : 0 Vs. You : X       
enter to play 1(st) or 2(nd) :
Enter your moves as numbers from 1 to 9, corresponding to the positions on the board. The board is arranged as follows:
-  -  -  
-  -  -  
-  -  - 
Play and enjoy the game!

Example Gameplay

Enter choice: 1

Player 1 (X), choose your move (1–9): 5
Current board:
-  -  -  
-  X  -  
-  -  -

AI (O) is making its move...

Current board:
-  O  -  
-  X  -  
-  -  -

Player 1 (X), choose your move (1–9): 1
...
How It Works
The game consists of a 3x3 board where players take turns marking their spot with an "X" or "O".
Players choose a position on the board by entering a number between 1 and 9. The board updates after every move, and the game checks for a winner.
In Single-player mode, the AI selects a random open spot for its move.
In Multiplayer mode, two human players take turns selecting positions on the board.
Extending the Project
This is a simple implementation, and there are plenty of ways to extend and improve it:

Enhance the AI to make smarter moves using a minimax algorithm or another strategy.
Add a score counter to keep track of wins and losses.
Implement a restart game option after a win or draw.
Add input validation to ensure players only input valid moves (numbers 1–9 for empty spots).
