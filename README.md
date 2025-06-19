# Tic-tac-toe game

## Overview

This is a simple console-based implementation of the classic Tic-Tac-Toe game using C++. The human player plays against the computer, which uses the **Minimax algorithm to make optimal moves.

## Algorithm Used

The computer uses the Minimax Algorithm for decision making. It explores all possible game states using recursion and chooses the move that maximizes its chances of winning while minimizing the chances for the opponent.

### Key Features of Minimax:
- Recursive backtracking to simulate every possible game outcome.
- Evaluation function returns:
  - +1 if the human wins,
  - -1 if the computer wins,
  - 0 for a draw.
- Computer always plays optimally.

## How to Compile and Run

### Prerequisites
- A C++ compiler like g++ installed on your system.

### Compilation Steps

1. Save the code in a file, e.g., tic_tac_toe.cpp.
2. Open a terminal in the directory where the file is saved.
3. Compile the program using the following command:
   ```bash
   g++ tic_tac_toe.cpp -o tic_tac_toe
