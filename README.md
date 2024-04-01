# Rock Paper Scissors Game

This is a simple command-line implementation of the classic game "Rock Paper Scissors" written in Python. The game allows the player to compete against the computer in a series of rounds until the player chooses to quit.

## How to Play

1. Run the Python script in your terminal or command prompt.
2. The game will display the current score (wins, losses, and ties).
3. Enter your move by typing one of the following letters:
   - 'r' for Rock
   - 'p' for Paper
   - 's' for Scissors
   - 'q' to Quit the game
4. The computer will randomly select its move.
5. The game will determine the winner of the round based on the following rules:
   - Rock beats Scissors
   - Scissors beats Paper
   - Paper beats Rock
   - If both players choose the same move, it's a tie.
6. The score will be updated accordingly.
7. The game will continue to the next round until the player chooses to quit.

## Requirements

- Python 3.x

## Code Overview

The code uses the following Python concepts and modules:

- `random` module to generate random moves for the computer.
- `sys` module to exit the game when the player chooses to quit.
- `while` loops to control the flow of the game.
- `if-elif-else` statements to determine the winner of each round.
- `input()` function to get the player's move.
- `print()` function to display messages and scores.

### The game logic is implemented as follows:

1. The player enters their move ('r', 'p', 's', or 'q').
2. The computer generates a random move.
3. The game compares the player's move with the computer's move and determines the winner based on the rules of Rock Paper Scissors.
4. The score is updated based on the result of the round.
5. The game continues to the next round until the player chooses to quit.


Feel free to modify and enhance the game as per your requirements. Enjoy playing Rock Paper Scissors!
