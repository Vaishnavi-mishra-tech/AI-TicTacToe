# Project Statement – Tic Tac Toe Game

## 1. Introduction
This project implements a console-based Tic Tac Toe game using Python.  
It serves as a beginner-friendly example of how to build an interactive program using functions, loops, conditionals, and game logic.

---

## 2. Objectives
The goal of the project is to:
- Build a functional two-player Tic Tac Toe console game.
- Demonstrate modular programming with Python functions.
- Validate user input and manage game state.
- Implement win detection and tie conditions.
- Provide a clean and simple user experience.

---

## 3. System Overview

### **A. Board Representation**
The board is stored in a Python list with 10 elements (index 0 unused).  
This allows easy mapping to Tic Tac Toe


### **B. Player Interaction**
- Player 1 selects X or O.
- Players choose board positions (1–9).
- Invalid moves are rejected with prompts.

### **C. Game Logic**
The program includes:
- Checking if a board position is free
- Placing markers (X/O)
- Detecting win conditions via 8 possible combinations
- Identifying a tie when all spaces are filled

### **D. Turn Management**
A random generator selects which player starts the game.

### **E. Replay Capability**
After each match, players can choose to play again or exit.

---

## 4. Win Conditions

The player wins if any of the following combinations all contain the same marker:

### **Rows**
- (1, 2, 3)  
- (4, 5, 6)  
- (7, 8, 9)

### **Columns**
- (1, 4, 7)  
- (2, 5, 8)  
- (3, 6, 9)

### **Diagonals**
- (1, 5, 9)  
- (3, 5, 7)

These 8 combinations form the complete win-check system.

---

## 5. Sample Console Output Screenshots

### **Game Start**
Welcome to Tic Tac Toe!
Player 1, choose X or O: X
Player 1 will go first.
Are you ready to play? Enter y or n: y

### **Board Display Example**
| | X | |
| | O | |
| |   | |

### **Win Message**
Player 2 has won!

### **Tie Scenario**
TIE GAME!
---

## 6. Conclusion
This Tic Tac Toe project demonstrates:
- Fundamental programming concepts  
- Turn-based game loop design  
- Error-free input handling  
- Clean console UI output  

It is suitable for beginners learning Python and provides a simple model for expanding into more advanced games or GUI-based projects.

