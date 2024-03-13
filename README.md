# Sustainable-Transportation-Solutions

This Python script utilizes the NetworkX library to represent a map of cities and roads, and it provides various algorithms for finding paths between two cities. The supported algorithms include Depth First Search (DFS), Breadth First Search (BFS), A* Search, and Dijkstra's Algorithm.

## Prerequisites

- Python 3.x
- NetworkX library (`pip install networkx`)
- Matplotlib library (`pip install matplotlib`)

## Map Representation
The map is represented as a graph using NetworkX. Cities are nodes, and roads between cities are edges with associated weights representing distances.

## Algorithms
The script supports the following navigation algorithms:

- Depth First Search (DFS)
- Breadth First Search (BFS)
- A* Search
- Dijkstra's Algorithm
  
## Input Validation
The script includes input validation for user-entered start and end points. It ensures that only valid city names are accepted.

## Visualization
The script uses Matplotlib to visually display the map with cities and roads. The user is prompted to input start and end points through the console.

## Output
After inputting the start and end points, the script displays the paths and total distances calculated by each algorithm.

Note: This README assumes that the user has Python and the required libraries installed on their machine.
