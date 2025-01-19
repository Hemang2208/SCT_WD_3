# Tic-Tac-Toe Game

This repository contains a **Tic-Tac-Toe Game** built with HTML, CSS, and JavaScript. It is a simple yet fun interactive game where two players alternate marking spaces on a 3x3 grid. The goal is to get three of the same symbols in a row, either horizontally, vertically, or diagonally.

This project is part of my Web Developer internship at **SkillCraft Technology**, and it demonstrates my skills in creating interactive web applications using modern web technologies.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)

## Project Overview

This is a **Tic-Tac-Toe** game where two players alternate to place either "X" or "O" in a 3x3 grid. The first player to align three symbols horizontally, vertically, or diagonally wins. If all spots are filled without a winner, the game results in a draw. The game offers buttons to **reset** the game or **start a new game**.

## Features

- **Interactive 3x3 Grid**: Players can click on the grid to place either "X" or "O".
- **Player Turn Indicator**: The game alternates turns between two players.
- **Winner Detection**: The game detects if any player has won.
- **Game Reset**: A button to reset the game at any time.
- **Game Draw**: Displays a message if the game ends in a draw.

## Technologies Used

- **HTML**: To structure the game layout and buttons.
- **CSS**: To style the game grid and user interface elements.
- **JavaScript**: To handle the game logic, including player turns, winner detection, and game reset functionality.

## Installation

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/Hemang2208/SCT_WD_3.git
   ```

2. **Navigate to the project folder**:
   ```bash
   cd tic-tac-toe-game
   ```

3. Open the `index.html` file in your browser to play the game.

## Usage

- **Start Playing**: Click any empty cell in the 3x3 grid to place an "X" or "O".
- **Reset Game**: Click the **Reset Game** button to reset the current game (but retain the player turns and grid status).
- **New Game**: Click the **New Game** button to start a fresh game.
- **Game Outcome**: A message will appear showing the winner or if the game ends in a draw.

## How It Works

### Game Logic:

- The game alternates between two players, "X" and "O", when they click on an empty square in the 3x3 grid.
- After each move, the game checks if either player has won by checking predefined win patterns (horizontal, vertical, and diagonal).
- If all 9 cells are filled without a winner, a message indicating a **Draw** is displayed.
- Once a player wins or the game is a draw, the grid becomes disabled to prevent further moves until the game is reset.
  
### JavaScript Functions:

- **`checkWinner()`**: This function checks the current state of the grid and identifies if there’s a winning combination for either "X" or "O".
- **`showWinner()`**: Displays the winner’s message when a player wins.
- **`gameDraw()`**: Shows a message indicating that the game ended in a draw.
- **`enableBoxes()`**: Resets the grid to allow further moves.
- **`disableBoxes()`**: Disables the grid to prevent further moves after the game ends.

### Event Listeners:
- **Grid Cells**: Each cell in the grid is clickable. Once clicked, the cell is filled with the player's symbol, and their turn is completed.
- **Reset Game Button**: Resets the game state to allow for a new round without changing the player turns.
- **New Game Button**: Resets the entire game, allowing players to start fresh.

## Contributing

Contributions are welcome! 
If you have suggestions for improvements or additional features, feel free to open an issue or submit a pull request.