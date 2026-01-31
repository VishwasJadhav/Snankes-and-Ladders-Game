# 🐍🎲 Snakes & Ladders – Python Console Game

A Python-based console implementation of the classic **Snakes & Ladders** game.  
This project was created as a **learning exercise** to strengthen my understanding of Python fundamentals and to practice converting real-world game rules into executable logic.

---

## 🎯 Why I Built This Project

The main reason for building this project was to:
- Practice **core Python concepts** in a fun, rule-based problem
- Improve my ability to **think logically and structurally**
- Learn how to manage **state, flow, and user interaction**
- Gradually evolve a simple idea into a more **scalable solution**

Instead of directly jumping into advanced concepts, I intentionally started with a **basic version** and then improved it step by step.

---

## 🎯 Project Objectives

- Simulate a real-world board game using Python
- Apply loops, conditionals, and data structures effectively
- Handle user input and edge cases correctly
- Improve code structure through iteration
- Understand how a single-player logic can be extended to multiplayer

---

## 🧪 Version 1: Single-Player Game

**Objective:** Learn and apply Python fundamentals

This version represents my **beginner stage** of Python learning.  
It focuses on implementing the core rules of Snakes & Ladders for a single player.

### What I Implemented
- Dice rolling using random number generation
- Player movement across the board
- Snakes and ladders using dictionaries
- Boundary condition (player cannot exceed position 100)
- Exit option during gameplay

### Concepts Practiced
- `while` loops
- Conditional logic
- Dictionaries
- Input handling
- Basic game flow control

📂 **File:** [snakes_ladders_single_player.ipynb]([https://github.com/VishwasJadhav/Snankes-and-Ladders-Game/blob/main/Vishwas%20Jadhav%20Resume.pdf](https://github.com/VishwasJadhav/Snankes-and-Ladders-Game/blob/main/Snakes_and_Ladders_SinglePlayer.ipynb))

---

## 🎮 Version 2: Multiplayer Game

**Objective:** Extend the game logic to support multiple players and improve structure

In this version, I enhanced the original game to support **multiple players**, which required managing multiple game states and turn-based logic.

### New Features Added in Multiplayer Version
- Support for **multiple players**
- Player name input and validation
- Turn-by-turn gameplay using index rotation
- Individual position tracking for each player
- Dynamic handling when a player exits the game
- Cleaner and more readable game loop

### What Changed Technically
- Introduced a **list of dictionaries** to store player data (`name` and `position`)
- Used **modulo arithmetic** to rotate turns correctly
- Added validation for number of players
- Improved control flow to handle player removal safely

### Concepts Practiced
- Data structures for state management
- Input validation
- Modulo-based turn control
- Writing scalable procedural logic

📂 **File:** `snakes_ladders_multiplayer.py`

---

## 🧠 Key Learnings from This Project
- Breaking down real-world rules into logical steps
- Managing multiple players and shared state
- Improving beginner code through iteration
- Writing clearer and more maintainable Python programs

---

## 🔧 Tech Stack
- Python
- NumPy (used for dice roll simulation)

---

## 🏁 Final Note
This project is intentionally **learning-focused** and reflects my growth in Python programming.  
It demonstrates how I approach problem-solving, improve code step by step, and build scalable logic from simple beginnings.

Feedback and suggestions are welcome.
