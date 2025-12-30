# CPP Snake
A classic Snake game built in C++ for the windows, created as part of an Intro to Game Design course to demonstrate core gameplay logic, real-time input handling, and game loop fundamentals.

## Overview
This project is a simple console-based Snake game written in C++, using real-time keyboard input and a continuous game loop.<br>
It was built to demonstrate a clear understanding of:
- Game loops and frame updates
- Real-time user input handling
- Basic game state management
- Collision detection
- Procedural rendering in a terminal environment

The game recreates the classic Snake experience using ASCII characters for rendering.

---

## Gameplay features include:
- Snake movement controlled via keyboard
- Randomly spawning fruit
- Growing snake tail
- Score tracking
- Game-over detection on self-collision
(Console-based game — no graphics or screenshots available)

## Skills Demonstrated
- C++ fundamentals
- Game loop design
- Real-time keyboard input (_kbhit, _getch)
- Collision detection (snake body & fruit)
- State-based game logic
- Console rendering and screen clearing
- Debugging logical and runtime errors

## Architecture
The game is structured around a simple loop-driven architecture:

### Setup
Initializes the game state, snake position, fruit position, and score.

### Input
Handles real-time keyboard input for snake movement and quitting the game.

### Logic
Updates snake position, tail behavior, collision checks, and scoring.

### Draw
Renders the game board, snake, fruit, and score using ASCII characters.

### Main Loop
Continuously calls Draw, Input, and Logic until the game ends.

---

## How to Run
### **Prerequisites**
- Windows OS
- Windows SDK (<window.h>)
- C++ compiler (Visual Studio recommended)

### **Setup**
- Open the project in Visual Studio
- Build the solution
- Run the executable 

---

## Controls
- W — Move Up
- A — Move Left
- S — Move Down
- D — Move Right
- X — Quit Game

## Game Rules
- Eat fruit (@) to increase score
- Each fruit increases the snake’s length
- Colliding with your own tail ends the game
- The snake wraps around the screen edges

---

## Technologies Used
- C++
- <conio.h> for keyboard input
- <windows.h> for timing (Sleep)

---

## Contact
**Isaac Hraga**
- GitHub: https://github.com/isaachraga
- LinkedIn: www.linkedin.com/in/isaac-hraga-5b7535b2
