# MazeSolver
Maze Solver README
==================

Description:
------------
This program is designed to solve a maze. A maze consists of open spaces (' ') and walls ('#'), a starting point 'S', and an ending point 'E'. The objective is to find a path from the starting point to the ending point.

Components:
-----------
1. **node Class**: Represents a point in the maze with `x` and `y` coordinates and a reference to the next node.
  
2. **IStack Interface**: Describes basic stack operations such as pop, peek, push, isEmpty, and size.

3. **IMazeSolver Interface**: Declares methods for solving the maze using Breadth First Search (BFS) and Depth First Search (DFS).

4. **Main Class (Maze Solver)**: Implements the `IMazeSolver` interface and contains methods to solve the maze. Includes:
    - Reading the maze from a file
    - Main menu to choose between DFS, BFS, or both
    - Maze traversal using BFS and DFS

5. **stack Class**: Implements the `IStack` interface using a linked list.

6. **IQueue Interface**: Describes basic queue operations like enqueue, dequeue, isEmpty, and size.

7. **queue Class**: Implements the `IQueue` interface using a linked list.

Usage:
------
1. The maze should be in a file with its dimensions specified on the first line (e.g., "5 7" for a maze of 5 rows and 7 columns).
2. Walls are represented by '#', open paths by ' ', the start point by 'S', and the end point by 'E'.
3. Run the main method, and you'll be prompted with options to solve the maze using DFS, BFS, or both.
4. The solution will then display the path from the start to the end point.

Note:
-----
- This program uses both BFS and DFS, so users can compare the efficiency and correctness of both methods.
- Make sure to have the maze file in the correct directory.
- Ensure the maze has valid starting and ending points.


