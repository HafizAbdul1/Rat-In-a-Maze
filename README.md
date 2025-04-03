# Rat-In-a-Maze
This project simulates the Rat-in-a-Maze experiment, a classic psychology study where a rat learns to navigate a maze to reach a food reward. The simulation tracks learning progress as the rat improves its navigation over multiple trials.
# Rat-in-a-Maze Simulation

## Overview
This project is a **C# console application** that simulates the "Rat-in-a-Maze" experiment. It models a rat navigating through a maze using a depth-first search (DFS) algorithm to find an exit.

## Features
- **Maze Representation**: Grid-based maze using a 2D array (`0 = path`, `1 = wall`).
- **Pathfinding Algorithm**: Uses **Depth-First Search (DFS)** to find the shortest path.
- **Multiple Movement Directions**: Rat can move in **8 possible directions**.
- **Simulation of Learning**: The rat learns to navigate the maze over repeated trials.

## Technologies Used
- **Language**: C#
- **Concepts Used**: Recursion, Depth-First Search, Object-Oriented Programming

## How It Works
1. The **maze** is created as a **6x8 grid** with walls (`1`) and open paths (`0`).
2. The **rat starts at an entry point** and explores possible paths to reach the exit.
3. The **FindPath() function** checks available moves and recursively finds a valid route.
4. If a path is found, it prints the steps taken by the rat.
