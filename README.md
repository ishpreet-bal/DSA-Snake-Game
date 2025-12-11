Multiplayer Snake Game Using DSA (C++) 🐍

This project recreates the classic Snake experience in C++ with support for two players. The core mechanics are built around fundamental data-structure and algorithm principles to ensure smooth, efficient gameplay.

Key Highlights ✨

Simultaneous two-player gameplay with separate control schemes

Continuous movement handling and robust collision logic

Growing snakes and randomly positioned food items

Runs entirely in the console for fast performance and easy portability

DSA Concepts Applied 📚

Linked Lists: Each snake’s body is stored as a linked list, enabling fast insertion and removal of segments as it moves or grows

Queues: Used to maintain the order of body segments for consistent movement updates

Collision Logic: Coordinate-based checks prevent snakes from running into walls, themselves, or each other

Random Number Generation: Determines valid, non-occupied positions for food placement

Game Loop Design: Combines input handling, state transitions, and screen rendering into a streamlined loop

Player Controls 🎮

Player 1: W / A / S / D

Player 2: Arrow keys

Build & Run Instructions ⚙️

Grab the repository:

git clone https://github.com/ishpreet-bal/DSA-Snake-Game.git


Open the project directory:

cd DSA-Snake-Game


Compile:

g++ -o snake_game main.cpp


Start the game:

./snake_game

How It Plays 🕹️

Guide your snake toward food to extend its length, but avoid hitting boundaries, yourself, or the other player’s snake. The match ends when a collision occurs—perfect for competitive or casual play.