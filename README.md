# Tic Tac Toe - Game


## Objective

"Tic Tac Toe - Game" is a project of common known game, that was coded as part of online course - "The Complete Python Bootcamp from Zero to Hero in Python" by Pierian-Data. The code was provided with slightly changed

It mainly consists of developign and implementing a computer program, coded in Python, that enables two Players to play Tic Tac Toe. 


## Basic Assumptions

* 2 players should be able to play the game (both sitting at the same computer)
* the board should be printed out every time a plater makes a move
* input of the player postion should be accept and place as a sumbol on the board


## Game Description

Tic-tac-toe is a game for two players who take turns marking the spaces in a three-by-three grid with X or O. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row is the winner.


## Game Rules

1. At the begining Players declare willigness to play. 

2. First Person decides, which symbol (token) he wants to play (X or O). Choosen symbol is assigned to Player 1, and second one to Player 2. 

3. A 3x3 board is qreated and presented to the Players:
   |   |
 X | X | O
   |   |
-----------
   |   |
 O | O | X
   |   |
-----------
   |   |
 X | O | X
   |   |

4. Player 1 and 2 take turns making moves:
- each Player decided in which field his symbol should be placed (the aim is to create a straight line horizontally, vertically or diagonally),
- after each move, program checks if one of the players gets three of his/her marks in a row (vertically, horizontally, or diagonally); if yes, that player wins the game
- if no one can create a straight line with their own mark and all the positions on the board are occupied, then the game ends in a tie.