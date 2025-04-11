# ❌⭕ Tic-Tac-Toe Game in C

## 📘 Overview

This project is a simple yet fun implementation of the classic **Tic-Tac-Toe (X-O) game**, developed in the **C programming language**. It allows two players to play against each other on a 3×3 grid in the command-line interface. The game logic ensures accurate win detection, draw handling, and smooth player switching.

---

## 🎮 Game Features

- Two-player mode (Player 1 = 'X', Player 2 = 'O')
- 3×3 grid display with automatic updates after each move
- Input validation to prevent overwriting existing cells
- Win and draw condition detection
- Replay option after game completion

---

## 🧠 Game Rules

- The game is played on a 3x3 grid.
- Players take turns to enter their move (X or O).
- A player wins by placing three of their marks in a horizontal, vertical, or diagonal row.
- If all 9 cells are filled and no player wins, the game ends in a draw.

---

## ⚙️ Technology Stack

- **C Language**: Used for core game logic and I/O
- **Standard I/O (stdio.h)**: For input and output operations
- **Custom functions**: To manage the board, check win/draw, and switch players

---

## 🧪 How to Compile and Run

1. **Compile the program**:
   ```bash
   gcc tic_tac_toe.c -o tic_tac_toe
