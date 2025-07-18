# Console Tic‑Tac‑Toe in C

A simple yet versatile command‑line Tic‑Tac‑Toe game in C featuring three game modes:

- **2‑Player**: Classic 3×3 gameplay between two human players  
- **3‑Player (4×4)**: Expanded mode with three players on a 4×4 grid  
- **Single‑Player vs. Computer**: Play against a basic AI opponent

## Motivation

This project is designed to:
- Teach fundamentals of C programming (arrays, control flow, functions)
- Demonstrate game‑loop logic and board handling
- Implement user input handling and simple AI for solo play
- Serve as a learning base for beginners in systems programming

## Features

- Clean console UI with clear prompts and board drawing  
- Input validation (e.g. checking for valid moves)  
- Win/draw detection for each game variant  
- Modular code structure (easy to extend or refactor)

## Getting Started

### Prerequisites

- A C compiler (e.g., `gcc`, `clang`)  
- Unix/Linux/macOS terminal or Windows with MinGW/Cygwin

### Build & Run

```bash
# Clone the repository
git clone https://github.com/<your‑username>/tic‑tac‑toe‑c.git
cd tic‑tac‑toe‑c

# Compile
gcc -std=c11 -o ttt main.c board.c ai.c

# Run
./ttt
