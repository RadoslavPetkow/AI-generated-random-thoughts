# Minesweeper Game

This is a simple web-based implementation of the classic Minesweeper game. The game is built using HTML, CSS, and JavaScript, and it runs directly in the browser.

## Features

- A 9x9 grid where 10 mines are randomly placed.
- Left-click on cells to reveal them.
- Right-click on cells to flag them as mines.
- Win the game by revealing all non-mine cells.
- Lose the game if you reveal a mine.
- Restart button to reset and start a new game.

## How to Play

1. **Objective**: Reveal all cells that do not contain mines.
2. **Reveal Cells**: Left-click on a cell to reveal it.
   - If the cell is a mine, the game ends.
   - If the cell is not a mine, it will show the number of neighboring mines.
3. **Flag Mines**: Right-click on a cell to flag or unflag it as a mine.
4. **Win Condition**: Reveal all non-mine cells without clicking on a mine.
5. **Restart**: Click the "Restart" button to start a new game.

## Game Interface

- The game board consists of a 9x9 grid.
- Each cell can be revealed or flagged.
- Revealed cells that are mines will show a bomb icon (💣).
- Revealed cells with neighboring mines will show the count of mines.
- Flagged cells will show a flag icon (🚩).

## Installation

No installation is required. Simply download the HTML file and open it in your browser to start playing.

## How to Run

1. Download the HTML file.
2. Open the file in a web browser (e.g., Chrome, Firefox).
3. Enjoy playing the Minesweeper game!

## Code Structure

- **HTML**: Sets up the game interface, including the game board and the restart button.
- **CSS**: Styles the game board, cells, and provides visual feedback for different game states (e.g., revealed, flagged).
- **JavaScript**: Contains the game logic, including grid creation, mine placement, cell revealing, flagging, and win/loss conditions.

## Game Logic

- **Grid Initialization**: A 9x9 grid is created with each cell initialized to be empty.
- **Mine Placement**: 10 mines are placed randomly on the grid.
- **Calculating Neighboring Mines**: Each non-mine cell calculates the number of neighboring mines.
- **Game Over**: The game ends when a mine is revealed, showing all mines on the board.
- **Win Condition**: The game is won when all non-mine cells are revealed.

## License

This project is open-source and free to use for personal and educational purposes.

## Acknowledgments

This game is inspired by the classic Minesweeper game and was built as a fun project to practice HTML, CSS, and JavaScript.
