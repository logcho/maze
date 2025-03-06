# Maze Solving with Goal-based Agent

## Student Name: Logan Choi

### AI Tools Used:
- ChatGPT

---

## Project Overview

This project implements a goal-based agent to solve a maze using various search algorithms. The agent uses a map of the maze to plan a path from the starting location to the goal location. The agent operates in a deterministic environment, where it can follow the path once the plan is made, without needing to consider percepts during execution. 

---

## Instructions

### Tasks

1. **Define the Search Problem:**
   - Initial State, Actions, Transition Model, Goal State, and Path Cost are defined.
   - The agent navigates the maze using the following directions: Up, Down, Left, Right.

2. **Uninformed Search Algorithms:**
   - Implement the following search strategies:
     - Breadth-First Search (BFS)
     - Depth-First Search (DFS)

3. **Heuristic Search Algorithms:**
   - Implement the following search strategies:
     - Greedy Best-First Search (GBFS)
     - A* Search

4. **Run Each Algorithm on Various Mazes:**
   - Solve the maze using the search algorithms and analyze the results.
   - Mazes to test include small, medium, large, open, wall, loops, empty, and empty 2-maze.

5. **Results Reporting:**
   - Report the solution, path cost, number of nodes expanded, maximum tree depth, and maximum size of the frontier.
   - Visualize the maze with the path and expanded nodes.

---

## Components

- **Maze Representation:**  
  The maze is represented as a 2D numpy array, where walls are denoted as 'X', the start as 'S', and the goal as 'G'.  
  Helper functions are provided to parse the maze and visualize the solution.

- **Node Class:**  
  The node structure is implemented for search algorithms. It includes methods for managing the state, parent node, action taken, and path cost.

---

## Requirements

- Python 3.x
- Numpy
- Matplotlib

You can install the required libraries using pip:

```bash
pip install numpy matplotlib
