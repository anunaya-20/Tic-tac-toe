# Tic-tac-toe game

## Overview

This is a basic text-based version of the classic Tic-Tac-Toe game developed in C++. The user competes against the computer, which makes decisions using the **Minimax algorithm to play intelligently.

## Algorithm Used

The computer's strategy is powered by the Minimax Algorithm. It systematically explores all possible moves and outcomes through recursion and selects the move that offers the best chance of success while reducing the opponent’s chances of winning.

### Key Features of Minimax:
- Utilizes recursive backtracking to evaluate all potential game states.
- The scoring function evaluates outcomes as follows:
  - +1 if the human wins,
  - -1 if the computer wins,
  - 0 for a draw.
- Ensures that the computer always makes the best possible move.

## How to Compile and Run

### Prerequisites
- Make sure you have a C++ compiler like g++ installed on your system.

### Compilation Steps

1. Save the code in a file, e.g., tic_tac_toe.cpp.
2. Open a terminal in the directory where the file is saved.
3. Compile the program using the following command:
   ```bash
   g++ tic_tac_toe.cpp -o tic_tac_toe
