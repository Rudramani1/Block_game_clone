# Raylib Tetris Clone

A classic Tetris-style block game implementation using C++ and the Raylib library.

<p align="center">
  <img src="preview.jpg" alt="Game Preview" width="600">
</p>

## 🎮 Features

- **Classic Gameplay**: Complete rows to clear them and score points.
- **7 Tetromino Types**: I, J, L, O, S, T, Z blocks.
- **Score System**: Points for clearing lines and soft dropping.
- **Next Block Preview**: See which piece is coming next.
- **Sound Effects & Music**: Background music and sound effects for rotation and line clearing.
- **Game Over State**: Detects when blocks stack too high.

## 🕹️ Controls

| Key | Action |
| --- | --- |
| **Left Arrow** | Move Block Left |
| **Right Arrow** | Move Block Right |
| **Down Arrow** | Move Block Down (Soft Drop) |
| **Up Arrow** | Rotate Block |

## 🛠️ How to Build & Run

### Prerequisites
- C++ Compiler (MinGW for Windows)
- [Raylib](https://www.raylib.com/) library
- Visual Studio Code (Recommended)

### Using VS Code (Windows)
1. Open the `main.code-workspace` file in Visual Studio Code.
2. Ensure you have the C/C++ extension installed.
3. Open `src/main.cpp`.
4. Press `F5` to compile and run the game.

<<<<<<< HEAD
=======
### Manual Build
If you have `make` installed and configured with Raylib:
```bash
make
```
>>>>>>> 5134f24 (Updated Preview.jpg)

## XY File Structure

- `src/`: Source code files (.cpp and .h)
- `Sounds/`: Game audio assets
- `Font/`: Game fonts
- `lib/`: Precompiled libraries

## � Credits

- Built with [Raylib](https://www.raylib.com/)
- Font: Monogram
