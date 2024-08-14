
---

# Tic-Tac-Toe with Unbeatable AI

This is a simple command-line Tic-Tac-Toe game implemented in Python. The game features an unbeatable AI opponent that uses the Minimax algorithm to always play optimally. The AI is designed to ensure it never loses to the human player.

## Features

- **Unbeatable AI:** The AI uses the Minimax algorithm to guarantee optimal play.
- **Human vs AI:** Play against the AI, which always makes the best move.
- **Simple and Interactive:** Easy-to-use command-line interface for a classic game experience.

## How to Play

### Prerequisites

- Python 3.x installed on your system.

### Installation

1. Clone or download the repository to your local machine.

   ```bash
   git clone https://github.com/yourusername/tic-tac-toe-ai.git
   cd tic-tac-toe-ai
   ```

2. Navigate to the directory containing the script.

   ```bash
   cd path_to_directory
   ```

### Running the Game

To start the game, simply run the `tic_tac_toe.py` script:

```bash
python tic_tac_toe.py
```

### Game Instructions

1. The game board is a 3x3 grid, and you will be playing as `X`.
2. The AI will play as `O`.
3. On your turn, input the row and column number (0, 1, or 2) where you want to place your `X`.
4. The AI will then make its move.
5. The game continues until either you win, the AI wins, or the game ends in a tie.

### Example Gameplay

```
Welcome to Tic-Tac-Toe!
  |   |  
-----
  |   |  
-----
  |   |  

Enter the row (0, 1, 2): 1
Enter the column (0, 1, 2): 1
  |   |  
-----
  | X |  
-----
  |   |  

AI's move:
  |   |  
-----
  | X |  
-----
  | O |  
```

## How It Works

- **Board Representation:** The board is represented as a 3x3 grid with each cell containing `" "`, `"X"`, or `"O"`.
- **Minimax Algorithm:** The AI evaluates all possible moves using the Minimax algorithm, choosing the move that maximizes its chances of winning.
- **Game Flow:** The player and AI alternate turns until there's a winner or the game ends in a tie.

## Contributing

Feel free to fork this repository and submit pull requests if you'd like to contribute improvements or additional features.


## Acknowledgements

This project was inspired by the classic game of Tic-Tac-Toe and serves as a practical implementation of the Minimax algorithm.

---

This README provides a clear overview of the project, instructions on how to play, and details about the underlying mechanics of the game.
