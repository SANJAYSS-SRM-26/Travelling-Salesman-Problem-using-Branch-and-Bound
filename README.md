# Traveling Salesman Problem using Branch and Bound

## Description
This C++ program solves the Traveling Salesman Problem (TSP) using the Branch and Bound algorithm. TSP is a classic problem in the field of computer science and optimization, where the goal is to find the shortest possible route that visits every city exactly once and returns to the original city.

## Features
- Efficiently finds the minimum cost tour using Branch and Bound.
- Handles a small number of cities efficiently.
- Uses adjacency matrix representation for the graph.

## Requirements
- C++ compiler (supporting C++11 or later)
- Standard Template Library (STL)

## Usage
1. Clone the repository.
2. Compile the `tsp.cpp` file using a C++ compiler.
3. Run the compiled executable.
4. The program will output the minimum cost and the path taken by the salesman.

## Sample Input
The program is initialized with the following adjacency matrix representing the distances between cities:
0 10 15 20
10 0 35 25
15 35 0 30
20 25 30 0

## Sample Output
Minimum cost : 80
Path Taken : 0 1 3 2 0
