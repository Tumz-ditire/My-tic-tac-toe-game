# My Tic-Tac-Toe Game

A simple, browser-based Tic-Tac-Toe game built with HTML, CSS and JavaScript. This repo contains a small interactive game where two players can play locally in the same browser window.

Demo / Files
- Start page: `Tic-tac-toe3-Startuppage.html` — a simple welcome popup that links to the game page.
- Game page: `Tic-tac-toe3.html` — the playable Tic-Tac-Toe board (linked from the start page).
- JavaScript logic: `Script.js` — contains the game logic (player turns, win/draw detection, restart).
- Stylesheet: `styles.css` — centralized styles extracted from the startup page.

Features
- Two-player local gameplay (players alternate between X and O)
- Win detection for rows, columns, and diagonals
- Draw detection
- Restart button to clear the board and play again
- Lightweight and easy to run in any modern browser

How it works (quick overview)
- The game uses a 3x3 board represented by an array of 9 cells in `Script.js`.
- `currentPlayer` toggles between "X" and "O" after each valid move.
- After every move, the script checks for a win (8 winning conditions) or a draw.
- The status message displays the current player's turn, a win message, or a draw message.

Usage
To run the game locally:
1. Clone the repository:

   git clone https://github.com/Tumz-ditire/My-tic-tac-toe-game.git

2. Open `Tic-tac-toe3-Startuppage.html` in your browser and click one of the player buttons to start the game.

Alternatively, serve the folder with a simple HTTP server and open the start page in the browser (useful if you want to avoid some browsers' local file restrictions):

- Python 3:

  python -m http.server 8000

  Then open http://localhost:8000/Tic-tac-toe3-Startuppage.html

Live demo (GitHub Pages)
You can publish the `main` branch with GitHub Pages to get a hosted demo. To enable Pages:

1. Go to your repository on GitHub > Settings > Pages.
2. Under Source, select the `main` branch and the `/ (root)` folder, then click Save.

After enabling, the demo will usually be available at:

https://Tumz-ditire.github.io/My-tic-tac-toe-game/

Note: GitHub Pages may take a minute to build. If the URL above doesn't work, check the Pages settings for the exact published URL.

Gameplay
- Click a cell to place the current player's mark (X or O).
- Players alternate turns automatically.
- A message shows whose turn it is, who won, or if the game ended in a draw.
- Click the Restart button to reset the board and start a new game.

Development & Customization
- Game messages and initial player can be changed in `Script.js`.
- Styling is now in `styles.css`; feel free to edit or move it into a different file.
- To change the starting player, update the `currentPlayer` variable in `Script.js`.

Contributing
Contributions are welcome. If you'd like to add features (single-player AI, score tracking, online multiplayer), open an issue or submit a pull request with a description of your changes.

License
This project is licensed under the MIT License — see the `LICENSE` file for details.

Contact
Repository owner: Tumz-ditire
