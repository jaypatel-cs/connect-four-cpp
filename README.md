# Connect Four (C++)

## Overview
A command-line implementation of the classic Connect Four game built in C++.  
Two players alternate dropping pieces into a 7x6 board until one player connects four in a row (horizontal, vertical, or diagonal).

## Features
- Two-player gameplay
- Board display after each move
- Input validation (prevents invalid columns / full columns)
- Win detection:
  - Horizontal
  - Vertical
  - Diagonal (both directions)
- Draw detection when the board is full

## Concepts Used
- Arrays / 2D board representation
- Functions and modular design
- Loops and conditionals
- Game-state tracking
- Basic algorithmic win checking

## How to Run
Compile:
```bash
g++ -std=c++17 -O2 -Wall -Wextra main.cpp -o connect4
