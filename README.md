# Simon Says Game

## Overview

This project is a simple interactive memory-based color game built using JavaScript. The game challenges users to replicate a sequence of colors displayed by the game, with the sequence becoming longer as levels progress.

## Features

- Generates a random color sequence with each level.
- Provides visual feedback for user actions and game events.
- Tracks and displays the current game level.
- Simple and lightweight code implementation.

## How It Works

The game follows this logic:

1. A keypress triggers the start of the game.
2. The function `levelup()` generates a random color and adds it to the game sequence.
3. The game flashes the corresponding button for the new color.
4. The user must click buttons to match the sequence.
5. The game checks the user's input:
   - If correct, the game progresses to the next level.
   - If incorrect, the game displays "Game Over" and resets.
