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
