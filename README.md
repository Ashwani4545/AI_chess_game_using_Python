# ♟️ AI Chess Game using Python

## 📘 Overview

This project is a **Python-based AI Chess Game** that allows a human player to compete against an intelligent computer opponent. It uses algorithms to evaluate board positions and determine the best possible moves, providing an engaging gameplay experience.

The AI utilizes **Minimax algorithm with Alpha-Beta pruning** to predict the player’s moves and optimize its strategy. The project is developed for educational purposes, demonstrating how AI can simulate strategic decision-making in board games.

---

## 🧠 Features

- Full chess game implementation with legal move validation
- Intelligent AI opponent using Minimax + Alpha-Beta pruning
- Move highlighting and real-time board updates
- Detects check, checkmate, and stalemate conditions
- Graphical User Interface built with `pygame`
- Restart and quit options in-game

---

## 🧩 Tech Stack

- **Language:** Python 3.x
- **Libraries:** `pygame`, `sys`, `random`, `copy`
- **Algorithm:** Minimax with Alpha-Beta Pruning

---

## ⚙️ Installation & Setup

#### 1️⃣ Clone the Repository

```
git clone https://github.com/Ashwani4545/AI_chess_game_using_Python.git
cd AI_chess_game_using_Python
```

#### 2️⃣ Install Dependencies

Make sure you have Python 3.x installed. Then install required libraries:

```bash
pip install pygame
```

#### 3️⃣ Run the Game

```
python main.py
```

_(If your entry file name differs, replace `main.py` with the correct one.)_

---

## 🎮 How to Play

- Start the game by running the main Python file.
- You (white pieces) will play first.
- Click on a piece to select it, then click on the destination square.
- The AI will automatically respond with its move.
- The game continues until checkmate, stalemate, or manual exit.

---

## 🏗️ Project Structure

```
AI_chess_game_using_Python/
│
├── assets/                 # Chess piece images and icons
├── main.py                 # Main game loop
├── chess_ai.py             # AI algorithm (Minimax, Alpha-Beta)
├── board.py                # Board setup and move validation
├── game.py                 # Handles turn management and status checks
├── LICENSE                 # MIT License file
└── README.md               # Project documentation
```

---

## 🧮 Algorithm Overview

The AI uses the **Minimax algorithm** enhanced with **Alpha-Beta pruning**:

- Evaluates all possible moves recursively.
- Prunes unnecessary branches to optimize performance.
- Assigns scores to board states based on material and positional value.

---

## 🧑‍💻 Contributors

- [Ashwani Pandey](https://github.com/Ashwani4545) — Developer & Maintainer

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## ⭐ Acknowledgments

Special thanks to the open-source community and Python developers who made libraries like `pygame` accessible and easy to use for game development.
