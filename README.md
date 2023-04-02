# Solving 8 Puzzle Problem using BFS and DFS

This project is a C++ implementation of solving the classic 8 puzzle problem using Breadth-First Search (BFS) and Depth-First Search (DFS) algorithms.

## Introduction

The 8-puzzle problem is a well-known problem in the field of artificial intelligence that requires finding a sequence of moves that transform a scrambled 3x3 grid of numbered tiles into the correct order. The objective is to find the shortest sequence of moves that solves the puzzle.

In this project, we implemented two search algorithms - BFS and DFS - to solve the 8-puzzle problem. The BFS algorithm searches the state space by exploring all the neighboring nodes first before moving to the next level, while the DFS algorithm explores as far as possible along each branch before backtracking.

## Implementation

This project is implemented in C++, and the `AI_final_project.cpp` file contains the main code for solving the 8-puzzle problem. The Node class represents a node in the search tree, and the Puzzle class contains the logic for generating the initial state of the puzzle, as well as the functions for checking the goal state and generating the successor nodes.

The BFS and DFS algorithms are implemented in the `AI_final_project.cpp` files, respectively. Both algorithms take a starting state of the puzzle as input and return a sequence of moves that solves the puzzle.

## Usage

To run the program, simply execute the `AI_final_project.cpp` file in your C++ environment:

```bash
g++ AI_final_project.cpp -o puzzle
./puzzle
```
The program will generate a random initial state of the puzzle and print out the sequence of moves to solve it using both BFS and DFS algorithms. The output will show the number of moves taken and the time taken to solve the puzzle.

## Conclusion

In conclusion, this project demonstrates how BFS and DFS algorithms can be used to solve the classic 8-puzzle problem in C++. The solution involves generating a search tree to explore the state space, and using these algorithms to search the tree for the shortest path to the goal state.
