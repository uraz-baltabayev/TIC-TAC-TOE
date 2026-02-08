# Tic-Tac-Toe (C++)

A simple **Tic-Tac-Toe game** implemented in **C++**.  
Play against another player in the console with a standard 3x3 grid.

---

## 🎮 Features

- 2-player mode (player vs player)  
- Console-based gameplay  
- Clear, interactive board display  
- Win, lose, and draw detection  

---

## 📦 Project Structure

TIC-TAC-TOE/
├── main.cpp # Game entry point
├── TicTacToe.cpp # Game logic implementation
├── README.md # Project documentation
└── .gitignore # Ignore rules

## 🛠️ Build & Run

### Prerequisites

- C++ compiler (G++, Clang, or MSVC)  
- CMake (optional, for build automation)

### Build with CMake

```bash
mkdir build
cd build
cmake ..
make

./TicTacToe

🎮 Controls
Players take turns entering row and column numbers to place their mark (X or O)
The game ends when a player wins or the grid is full (draw)

📜 License
This project is open-source — feel free to use and modify it.