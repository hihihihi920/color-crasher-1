
# Color Crasher

Color Crasher is a 3D endless runner game developed in Unity where players dodge incoming obstacles, collect coins, and try to achieve the highest score possible. The project demonstrates essential Unity game development concepts such as object pooling, collision detection, UI management, prefabs, and Android deployment.

## Features

- 🎮 Endless runner gameplay
- 🪙 Collectible rotating coins
- 🚧 Dynamic obstacle spawning
- ⚡ Increasing player speed as coins are collected
- 🏆 High score system
- 📊 Real-time score UI
- ♻️ Object Pooling system for optimized performance
- 📱 Android build support
- 🎨 Prefab-based game architecture

## Built With

- Unity 2023.2.19f1
- C#
- Unity UI
- Physics & Collision System

## Gameplay

The player continuously moves forward while avoiding obstacles and collecting coins.

Collecting coins:
- Increases the player's score
- Increases movement speed
- Updates the high score when a new record is achieved

Instead of constantly creating and destroying coin objects, the game uses an **Object Pooling** system to recycle game objects, improving performance and reducing memory allocations.

## Project Structure
