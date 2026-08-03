# Tic-Tac-Toe-Python

A simple, interactive 2-player Tic-Tac-Toe game built with Python and Tkinter.

## 📌 Features

* **Graphical User Interface (GUI):** Built using Python's native `tkinter` module.
* **Turn-Based Gameplay:** Switches automatically between Player `X` and Player `O`.
* **Win & Draw Detection:** Checks rows, columns, and diagonals for a winning line or a tied board after every move.
* **Validation:** Prevents players from overwriting an already occupied cell.
* **Auto-Reset:** Resets the game board automatically when a match ends.

---

## 🏃 How to Run

1. **Clone the repository:**
   
   ```bash
   git clone [https://github.com/your-username/tic-tac-toe-tkinter.git](https://github.com/your-username/tic-tac-toe-tkinter.git)
   cd tic-tac-toe-tkinter
3. Run the game:
   
   ```bash
   python main.py
   
## 🎮 How to Play
  -Player X always takes the first move.
  -Click on any empty cell on the 3x3 grid to place your mark.
  -The game will automatically detect when a player gets 3 marks in a row (horizontally, vertically, or diagonally) or if the board is full (Draw).

A popup window will announce the winner or a draw, and the board will clear automatically for a new game.

🛠️ Project Structure
Plaintext
├── main.py          # Core game logic and Tkinter GUI implementation
└── README.md        # Project documentation
