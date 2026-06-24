# Computer Vision Tic-Tac-Toe Robot

An embedded AI and robotics project that combines computer vision and robotic automation to create an autonomous Tic-Tac-Toe system. The project uses an OpenMV camera for board and move detection and a WLKATA Mirobot robotic arm to physically play against a human player.

---

## Project Overview

<img width="767" height="582" alt="image" src="https://github.com/user-attachments/assets/fd4c7421-038d-4748-8c16-253a09fbb525" />


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
<img width="400" height="270" alt="image" src="https://github.com/user-attachments/assets/e783ed98-a7e7-41b4-867d-f28c269d9cbb" />

### Piece Recognition
<img width="400" height="270" alt="image" src="https://github.com/user-attachments/assets/99f0eeb3-5321-4d57-8270-94a11d1b33cf" />


### Robot Playing
<img width="400" height="270" alt="image" src="https://github.com/user-attachments/assets/f18c87c9-258e-472c-a686-0036ac0584cb" />


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
