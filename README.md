# Tic Tac Toe Bot 🎮

A Tic Tac Toe game with an unbeatable AI opponent, built with Python and Pygame. The AI uses the **Minimax algorithm** to always play optimally — your best outcome is a draw!

---

## Features

- **Unbeatable AI** — the bot uses Minimax to evaluate every possible move and always picks the best one
- **Color-coded game over screen** — green if you win, red if the AI wins, grey for a draw
- **Instant restart** — press `R` to reset the board at any time

---

## How to Play

- You are **O** (circle) — click any empty square to place your piece
- The AI is **X** (cross) — it moves automatically after your turn
- Try to get three in a row horizontally, vertically, or diagonally
- Press **R** to restart

---

## Requirements

- Python 3.x
- [Pygame](https://www.pygame.org/)
- [NumPy](https://numpy.org/)

Install dependencies:

```bash
pip install pygame numpy
```

---

## Running the Game

```bash
python main.py
```

---

## How the AI Works

The AI is powered by the **Minimax algorithm** — a classic recursive decision-making algorithm used in two-player games. It simulates all possible future moves, scores the resulting board states, and always picks the move that maximizes its own chances while minimizing yours.

Since Tic Tac Toe is a solved game with no pruning optimizations needed, the AI evaluates the full game tree and plays a perfect game every time.

---

## Project Structure

```
tic-tac-toe-bot/
├── main.py      # Game logic, rendering, and AI
└── README.md
```

---

## License

This project is open source. Feel free to fork and experiment!
