# Pacman-AI Game

![Pacman-AI](/images/game_view.png)

This is a Pacman game with AI implementations of popular search algorithms, including Breadth-First Search (BFS), Depth-First Search (DFS), A* Search, and Uniform Cost Search. The game allows you to see how these algorithms perform in finding the optimal path for Pacman to navigate through the maze.
This repository is a fork from the profile [aahuja9/Pacman-AI](https://github.com/aahuja9/Pacman-AI).

## Table of Contents
- [Getting Started](#getting-started)
- [How to Play](#how-to-play)
- [Search Algorithms](#search-algorithms)
  - [BFS](#bfs)
  - [DFS](#dfs)
  - [A* Search](#a-search)
  - [Uniform Cost Search](#uniform-cost-search)
- [Multi Agent Algorithms](#search-algorithms)
  - [MinMax](#minmax)
  - [Alpha-Beta](#alpha-beta)
- [Screenshots](#screenshots)
- [License](#license)

## Getting Started

To get started, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/garpereira/pacman-ai.git
   cd pacman-ai
   ```

2. Run the game:
   ```bash
   python pacman.py
   ```

## How to Play

Use the arrow keys to control Pacman's movement within the maze. The goal is to eat all the dots while avoiding ghosts. Each search algorithm will control Pacman's movement, and you can observe how they perform in finding the best path.

## Search Algorithms

### BFS

Breadth-First Search explores all the neighbor nodes at the current depth before moving on to the nodes at the next depth level. It guarantees the shortest path in terms of the number of moves.

### DFS

Depth-First Search explores as far as possible along a branch before backtracking. It doesn't guarantee the shortest path.

### A* Search

A* Search uses a heuristic to estimate the cost from the current node to the goal and combines it with the actual cost to reach that node. It is informed and often finds the shortest path efficiently.

### Uniform Cost Search

Uniform Cost Search explores nodes with the least cost first. It guarantees the shortest path in terms of the cost of moves.

##  Multi Agent Algorithms

### MinMax

### Alpha-Beta

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it according to the terms of the license.
