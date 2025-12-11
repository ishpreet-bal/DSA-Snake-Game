# Multiplayer Snake Game Using DSA (C++) 🐉

A modern take on the classic Snake game, implemented in C++ with full support for two-player gameplay. The mechanics are built around core data structures and algorithms to ensure smooth movement, clean logic, and responsive controls.

## Key Highlights ⭐

- Two players can play at the same time with separate control sets  
- Real-time snake motion with reliable collision handling  
- Snakes grow as they eat food that appears at random positions  
- Console-based interface for lightweight execution and easy portability  

## Data Structures & Algorithms Used 🧠

### Linked Lists
Each snake's body is represented as a linked list, allowing efficient growth and segment updates during movement.

### Queues
Used to maintain and update the order of snake segments for seamless directional changes.

### Collision Detection
Coordinate comparisons ensure snakes cannot pass through walls, themselves, or each other.

### Random Generation
Food spawns at random valid coordinates using pseudo-random number generation.

### Game Loop
A carefully structured loop manages input polling, game-state updates, and rendering.

## Player Controls 🎯

- **Player 1:** `W` / `A` / `S` / `D`  
- **Player 2:** Arrow Keys (↑ ↓ ← →)

## Build & Run Instructions 🛠️

### 1. Clone the repository:
```bash
git clone https://github.com/yashp1932/DSA-Snake-Game.git

2. Enter the project folder:
cd DSA-Snake-Game

3. Compile the game:
g++ -o snake_game main.cpp

4. Run the executable:
./snake_game

Gameplay Overview 🎮

Control your snake, eat food to grow, and avoid collisions with walls, yourself, or the other player's snake. The game ends when a collision occurs—making it great for quick, competitive matches or casual play.
