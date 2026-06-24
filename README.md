# Computer Vision Tic-Tac-Toe Robot

An embedded AI and robotics project that combines computer vision and robotic automation to create an autonomous Tic-Tac-Toe system. The project uses an OpenMV camera for board and move detection and a WLKATA Mirobot robotic arm to physically play against a human player.

---

## Project Overview

![Robot Setup](images/setup.jpg)

The system continuously monitors the Tic-Tac-Toe board, detects the player's move using image processing techniques, calculates the optimal response, and commands the robotic arm to place its piece automatically.

---

## Features

- Real-time Tic-Tac-Toe board detection
- Computer vision-based move recognition
- Automated game state tracking
- AI-driven move decision logic
- Robotic arm control using UART communication
- Physical piece placement using G-code commands

---

## Technologies Used

- Python
- OpenMV
- WLKATA Mirobot
- Computer Vision
- UART Communication
- G-Code
- Embedded Systems

---

## System Workflow

Human Move
↓
OpenMV Camera Processing
↓
Image Filtering & Blob Detection
↓
Game State Update
↓
AI Decision Logic
↓
UART Communication
↓
WLKATA Mirobot Movement
↓
Robot Places Piece

---

## Screenshots

### Board Detection
![Board Detection](images/board-detection.jpg)

### Piece Recognition
![Piece Detection](images/piece-detection.jpg)

### Robot Playing
![Robot Action](images/robot-action.jpg)

---

## Implementation Highlights

- Developed image processing algorithms to identify board cells and game pieces.
- Implemented real-time move detection using blob recognition and filtering techniques.
- Designed game decision logic to calculate the robot's next move.
- Integrated OpenMV and WLKATA Mirobot through UART communication and G-code commands.
- Conducted iterative testing and debugging to improve recognition accuracy and movement reliability.

---

## What I Learned

This project strengthened my understanding of:

- Computer vision fundamentals
- Embedded system development
- Hardware-software integration
- Serial communication protocols
- Robotic motion control
- Real-time debugging and testing

---

## Future Improvements

- Minimax algorithm implementation
- Improved lighting robustness
- Dynamic board calibration
- Voice command support

---

## Author

Joseph Nozal
Bachelor of Engineering in Digital Engineering
Thai-Nichi Institute of Technology
