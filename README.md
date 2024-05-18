# 2048 Game in Pygame

![2048 Game Screenshot](screenshot.png)

A Python implementation of the classic 2048 game using Pygame. Slide numbered tiles on a grid to combine them and create a tile with the number 2048.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Controls](#controls)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project is a simple and enjoyable version of the 2048 game. It uses Pygame to handle graphics and user input, providing a smooth and interactive experience. The game starts with two tiles of value 2 at random positions. Players can move the tiles using the arrow keys, and when two tiles with the same number collide, they merge into one with the sum of their values. The goal is to create a tile with the number 2048.

## Features

- Smooth tile movement and merging animations
- Random tile generation (2 or 4) after each move
- Simple, clean, and intuitive user interface
- Basic game-over detection

## Installation

### Prerequisites

- **Python:** Make sure you have Python installed. You can download it from [python.org](https://www.python.org/downloads/).

### Installing Python

1. **Download Python:**
   - Visit the [official Python website](https://www.python.org/downloads/).
   - Download the latest version of Python for your operating system.

2. **Install Python:**
   - Run the downloaded installer.
   - Make sure to check the box that says "Add Python to PATH" during the installation process.
   - Follow the installation instructions.

3. **Verify the Installation:**
   - Open a terminal (Command Prompt on Windows, Terminal on macOS/Linux).
   - Type `python --version` and press Enter. You should see the installed Python version.

### Installing Pygame

1. **Open a Terminal:**
   - On Windows: Open Command Prompt.
   - On macOS/Linux: Open Terminal.

2. **Install Pygame:**
   - Run the following command to install Pygame using `pip` (Python's package installer):
     ```bash
     pip install pygame
     ```

3. **Verify the Installation:**
   - Open a Python interactive shell by typing `python` and pressing Enter.
   - In the Python shell, type the following:
     ```python
     import pygame
     print(pygame.__version__)
     ```
   - If no errors appear and the version number is printed, Pygame is successfully installed.

### Running the Game

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/2048-pygame.git
   cd 2048-pygame

  ## How to Play

- Use the arrow keys to move the tiles.
- When two tiles with the same number collide, they merge into one.
- The objective is to reach the tile with the number 2048.
- The game ends when no more moves are possible.

## Controls

- **Left Arrow:** Move tiles left
- **Right Arrow:** Move tiles right
- **Up Arrow:** Move tiles up
- **Down Arrow:** Move tiles down

## Contributing

Contributions are welcome! If you have any ideas to improve the game, find any bugs, or want to add new features, feel free to open an issue or create a pull request.


