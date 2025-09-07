# Tic-Tac-Toe AI - CS50 AI Project

This project was completed as part of Harvard's [CS50 AI course](https://cs50.harvard.edu/). It implements an AI to play Tic-Tac-Toe optimally using the Minimax algorithm.

---

## Table of Contents

* [Overview](#overview)
* [Setup](#setup)
* [Game Logic](#game-logic)
* [Implementation](#implementation)
* [Usage](#usage)
* [Requirements](#requirements)
* [Acknowledgements](#acknowledgements)

---

## Overview

The project uses the Minimax algorithm to play Tic-Tac-Toe optimally. Once implemented, the AI cannot be beaten if both players play optimally.

The main files:

* `tictactoe.py`: Contains game logic and Minimax AI.
* `runner.py`: Runs the graphical interface for the game (provided).

---

## Setup

1. Download the project files: [tictactoe.zip](https://cdn.cs50.net/ai/2023/x/projects/0/tictactoe.zip)
2. Unzip the folder.
3. Install the required Python package:

```
pip3 install -r requirements.txt
```

---

## Game Logic

Functions implemented in `tictactoe.py`:

* `player(board)`: Returns which player's turn it is.
* `actions(board)`: Returns all possible moves.
* `result(board, action)`: Returns the board after a move.
* `winner(board)`: Returns the winner if there is one.
* `terminal(board)`: Checks if the game is over.
* `utility(board)`: Evaluates the board's utility.
* `minimax(board)`: Returns the optimal move for the current player.

The board is represented as a 3x3 list of lists, with `X`, `O`, or `EMPTY` in each cell.

---

## Implementation

Complete the required functions in `tictactoe.py`. You may add helper functions as needed. Ensure that the original board is not modified in `result`, as Minimax evaluates multiple states.

Optional: Implement alpha-beta pruning to improve AI efficiency.

---

## Usage

Run the game with Python 3.12:

```
python runner.py
```

Play against the AI through the graphical interface.

---

## Requirements

* Python 3.12
* Pygame (installed via `requirements.txt`)
* Only standard library modules

---

## Acknowledgements

* Completed as part of Harvard CS50 AI course.
* Inspired by classical Minimax algorithm for game theory.
