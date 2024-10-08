# Tic Tac Toe Game with Pygame

This is a simple Tic Tac Toe game implemented using Pygame. The game allows a player to play against a basic AI. The AI can make strategic moves to either win or block the player from winning.

## Features

- **Single Player Mode**: Play against the computer (AI).
- **Basic AI**: The AI prioritizes winning, blocking the player, and making strategic moves.
- **Graphical Interface**: The game is played on a 3x3 grid with X and O symbols.

## Installation

1. **Clone the repository**:
    ```bash
   https://github.com/User719-blip/ttt_ai.git
    ```

2. **Install Pygame**:
    You need to have Python installed on your system. You can install the required Pygame library using pip:
    ```bash
    pip install pygame
    ```

3. **Add Images**:
    Ensure that you have the following images in the same directory as the script:
    - `Blank.png`: An image representing an empty square.
    - `x.png`: An image representing the X player.
    - `o.png`: An image representing the O player.
    - `Background.png`: An image for the game background.
    - `X Wins.png`: An image to display when X wins.
    - `O Wins.png`: An image to display when O wins.
    - `Tie Game.png`: An image to display when the game ends in a tie.

## How to Play

1. **Run the game**:
    ```bash
    python tictactoe.py
    ```

2. The game window will open, showing a 3x3 grid.
   
3. **Player X**:
   - Click on any empty square to place your X.
   
4. **Computer AI**:
   - The computer will then place an O in response.

5. **Winning the Game**:
   - The game checks for winning combinations after each move.
   - If either player gets three in a row, a win message will be displayed.
   - If all squares are filled without a winner, a tie message will be shown.

6. **Quit the Game**:
   - Close the window or press `ESC` to exit the game.

## Game Logic

- The board is represented by a list of 10 elements (index 0 is unused).
- Winning combinations are pre-defined.
- The AI checks for immediate wins, blocks the opponent, and makes strategic moves.

## Contributing

Feel free to contribute to this project by submitting pull requests or opening issues.

 
