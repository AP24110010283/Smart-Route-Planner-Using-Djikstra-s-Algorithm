# Smart Route Planner Using Dijkstra's Algorithm (C++)

A C++ console application that models a road network as an undirected weighted graph. The application computes the shortest path between a source and destination while forcing traversal through user-specified intermediate nodes.

By leveraging Dijkstra’s algorithm to calculate individual segment distances, the tool provides a full path breakdown and the total cumulative distance. This project is ideal for learning graph algorithms, pathfinding with constraints, and interactive CLI design.

## Features
*   **Dynamic Road Network:** Add roads (edges) between locations with arbitrary weights.
*   **Constraint-Based Pathfinding:** Find the shortest path that must pass through custom intermediate nodes.
*   **Detailed Output:** Displays a segment-by-segment route and the total travel distance.
*   **Interactive UX:** Simple, easy-to-use menu-driven interface.

## Technical Overview
*   **Language:** C++
*   **Algorithm:** Dijkstra’s Algorithm
*   **Data Structure:** Adjacency List (Graph)
*   **Interface:** Command Line (CLI)
