# 🖤 Team Quantum Chess Game ♟️

## 📋 Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Project Structure](#project-structure)
- [Usage](#usage)

## 📖 Introduction
The **BlackWidow Chess Game** is a classic two-player chess game developed in Java. This project aims to provide an interactive digital chessboard where players can engage in a game of strategy and skill. The game adheres to all standard chess rules, including special moves like castling, en passant, and pawn promotion.

The application is built using **Java** for the core logic and **Swing** for the graphical user interface (GUI). Additionally, it incorporates a **MySQL** database to store game histories, player data, and move sequences, enabling players to save and review their games.

## ✨ Features
- Interactive graphical chessboard.
- Supports all standard chess rules (check, checkmate, stalemate, draw).
- Special moves: Castling, En Passant, Pawn Promotion.
- Player vs Player mode.
- Move validation and game state checks.
- Database integration to save and load games.
- Modular and maintainable code structure using Object-Oriented Programming (OOP) principles.

## 📂 Project Structure
ChessGameProject/
├── src/
│   └── com/
│       └── chess/
│           ├── Main.java               
│           ├── board/
│           │   ├── Board.java          
│           │   ├── Square.java         
│           ├── pieces/
│           │   ├── Piece.java          # Base class for all chess pieces
│           │   ├── Pawn.java           
│           │   ├── Rook.java           
│           │   ├── Knight.java         
│           │   ├── Bishop.java         
│           │   ├── Queen.java          
│           │   ├── King.java           
│           ├── gui/
│           │   ├── Table.java          
│           ├── database/
│           │   ├── DatabaseConnection.java 
│           │   ├── PlayerDAO.java      
│           │   ├── GameDAO.java        
│           ├── moves/
│           │   ├── Move.java           
│           │   ├── MoveValidator.java  
├── assets/                             
├── README.md                           
└── .gitignore                          

## 📚 Usage

-Start a New Game: Run the application and click on the "New Game" button.

-Move Pieces: Click on a piece and then click on a valid square to move it.

-Save Game: Option to save your game and resume later.

-View Game History: Review past games using the database.





This project is a fully functional chess game developed in Java. It includes essential gameplay mechanics, robust error handling, seamless component integration, and advanced event handling to deliver an engaging and reliable user experience.

---

## Key Development Tasks

### 1. Core Feature Implementation
- **Chessboard Setup**:
  - 8x8 board initialized with standard chess starting positions.
  - All chess pieces (pawns, rooks, knights, bishops, queen, and king) are fully implemented.
  
- **Movement and Rules**:
  - Validations for piece-specific movements (e.g., bishops move diagonally, knights in an "L" shape).
  - Rules enforced, such as castling, en passant, and pawn promotion.
  
- **Game State Management**:
  - Turn-based gameplay.
  - Check, checkmate, stalemate, and draw detection.

---

### 2. Error Handling and Robustness
- **Input Validation**:
  - Ensures user inputs are within valid bounds.
  - Prevents invalid moves and provides descriptive error messages.

- **Edge Case Handling**:
  - Handles complex scenarios like threefold repetition and insufficient material for a checkmate.
  
- **Database Error Management**:
  - Implements try-catch blocks for database connectivity issues.
  - Displays meaningful error messages for SQL exceptions.
  
- **GUI Fault Tolerance**:
  - Prevents the application from crashing due to unexpected user actions.

---

### 3. Integration of Components
- **GUI and Backend Logic**:
  - Real-time updates to the graphical interface after each move.
  - Integration of user inputs with the game engine and database operations.

- **Database Connectivity**:
  - Player profiles, match results, and move histories stored and retrieved from a MySQL database.
  
- **Testing and Debugging**:
  - Ensures all components function cohesively without conflicts.

---

### 4. Event Handling and Processing
- **User Interaction**:
  - Mouse-based controls for selecting and moving pieces.
  - Highlights valid moves when a piece is selected.

- **Timers and Clocks**:
  - Implements a chess clock for timed gameplay.
  - Automatically triggers events when a player's time runs out.

- **Real-Time Updates**:
  - Dynamic board updates based on player actions.
  
- **Undo/Redo Functionality**:
  - Allows users to reverse or redo moves to improve gameplay flexibility.

---

This project is designed to be scalable and maintainable, ensuring a smooth and enjoyable chess experience for all users.
