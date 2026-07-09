# My Tic-Tac-Toe Game

A simple, browser-based Tic-Tac-Toe game built with HTML, CSS and JavaScript. This repo contains a small interactive game where two players can play locally in the same browser window.

## Demo / Files
- Start page: `Tic-tac-toe3-Startuppage.html` — a simple welcome popup that links to the game page.
- Game page: `Tic-tac-toe3.html` — the playable Tic-Tac-Toe board (linked from the start page).
- JavaScript logic: `Script.js` — contains the game logic (player turns, win/draw detection, restart).
- Screenshot: `Tic tac toe game.PNG` — a visual of the project.

## Features
- Two-player local gameplay (players alternate between X and O)
- Win detection for rows, columns, and diagonals
- Draw detection
- Restart button to clear the board and play again
- Lightweight and easy to run in any modern browser

## How it works (quick overview)
- The game uses a 3x3 board represented by an array of 9 cells in `Script.js`.
- `currentPlayer` toggles between "X" and "O" after each valid move.
- After every move, the script checks for a win (8 winning conditions) or a draw.
- The status message displays the current player's turn, a win message, or a draw message.

## Usage
To run the game locally:
1. Clone the repository:

   git clone https://github.com/Tumz-ditire/My-tic-tac-toe-game.git

2. Open `Tic-tac-toe3-Startuppage.html` in your browser and click one of the player buttons to start the game.

Alternatively, serve the folder with a simple HTTP server and open the start page in the browser (useful if you want to avoid some browsers' local file restrictions):

- Python 3:

  python -m http.server 8000

  Then open http://localhost:8000/Tic-tac-toe3-Startuppage.html

## Gameplay
- Click a cell to place the current player's mark (X or O).
- Players alternate turns automatically.
- A message shows whose turn it is, who won, or if the game ended in a draw.
- Click the Restart button to reset the board and start a new game.

## Development & Customization
- Game messages and initial player can be changed in `Script.js`.
- Styling is contained in the HTML files (inline CSS in the startup page); you can move styles to a separate CSS file for easier maintenance.
- To change the starting player, update the `currentPlayer` variable in `Script.js`.

## Contributing
Contributions are welcome. If you'd like to add features (single-player AI, score tracking, online multiplayer), open an issue or submit a pull request with a description of your changes.

## License
This project is provided as-is. If you want this repository to include a formal license (MIT, Apache, etc.), let me know and I can add a LICENSE file.

## Contact
Repository owner: Tumz-ditire

Enjoy playing and customizing the game!
