# Tic Tac Toe - Game


## Objective

"Tic-Tac-Toe - Game" is a project of a commonly known game, that was coded as part of an online course called "The Complete Python Bootcamp from Zero to Hero in Python" by Pierian-Data. The code was provided with some slight changes regarding communication with the Players (adding additional messages about the game).

It mainly consists of developing and implementing a computer program, coded in Python, that enables two Players to play Tic Tac Toe. 

## Basic Assumptions

* 2 Players should be able to play the game (both sitting at the same computer)
* the board should be printed out every time a Player makes a move
* the input of the Player's position should be accepted and placed as a symbol on the board


## Game Description

Tic-Tac-Toe is a game for two Players who take turns marking the spaces in a three-by-three grid with X or O. The Player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row is the winner.


## Game Rules

1. At the beginning, Players declare their willingness to play. 

2. The first person decides, which symbol (token) he wants to play (X or O). Chosen symbol is assigned to Player 1, and the second one to Player 2. 

3. A 3x3 board is created and presented to the Players:

4. Player 1 and 2 take turns making moves:
- each Player decided in which field his symbol should be placed (the aim is to create a straight line horizontally, vertically or diagonally),
- after each move, program checks if one of the Players gets three of his/her marks in a row (vertically, horizontally, or diagonally); if yes, that Player wins the game,
- if no one can create a straight line with their own mark and all the positions on the board are occupied, then the game ends in a tie.
