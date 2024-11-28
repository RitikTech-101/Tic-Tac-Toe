# Tic-Tac-Toe Game

This is a simple **Tic Tac Toe** game built using **HTML**, **CSS**, and **JavaScript**. The game allows two players to take turns marking spaces on a 3x3 grid, with the goal of getting three of their marks in a row (horizontally, vertically, or diagonally).

## Features:
- **Two-player mode**: Players can take turns on the same device.
- **Interactive UI**: The game provides a simple, clean interface where players can click on the grid to make their moves.
- **Game state tracking**: The game tracks the state of the grid, including determining when a player wins, when the game is a draw, and automatically resets after a game ends.
- **Responsive design**: The layout is responsive, so the game will work on various screen sizes, including desktops and mobile devices.
- **Restart option**: Players can restart the game once it's over with a button that resets the grid.

## Technologies Used:
- **HTML**: Structure of the game interface, including the 3x3 grid and buttons.
- **CSS**: Styling for the grid and interface elements, including hover effects and animations.
- **JavaScript**: Game logic and event handling, including the mechanics for alternating turns, detecting wins, and checking for draws.

## Game Mechanics:
1. Players take turns by clicking on an empty cell in the 3x3 grid.
2. The first player uses "X" and the second player uses "O".
3. The game checks for a winner after each move:
   - A player wins by aligning three marks in a row (horizontal, vertical, or diagonal).
4. If all cells are filled without a winner, the game declares a draw.
5. After the game ends, the option to restart the game is presented.

## How to Play:
1. Clone or download the repository to your local machine.
2. Open the `index.html` file in a web browser to start the game.
3. Click on an empty cell to place your mark. Player 1 (X) and Player 2 (O) will alternate turns.
4. After the game ends, click "Restart" to play again.

## Installation:
1. Clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/your-username/tic-tac-toe.git
   ```
2. Navigate to the project directory:
   ```bash
   cd tic-tac-toe
   ```
3. Open the `index.html` file in any web browser to play the game.

## Demo:
You can play the game live [here](https://your-demo-link.com).

## Contributing:
If you'd like to contribute to this project, feel free to fork the repository, create a new branch, and submit a pull request with your changes.

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
