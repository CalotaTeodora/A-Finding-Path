# A* Path Finding Algorithm in Pygame

This Python script demonstrates the A* pathfinding algorithm using the Pygame library. The algorithm finds the shortest path between two points on a grid.

## Instructions

1. **Dependencies:**
   - Ensure you have Python installed on your system.
   - Install the required libraries using the following command:

     ```
     pip install pygame
     ```

2. **How to Run:**
   - Run the script by executing the following command:

     ```
     python filename.py
     ```

3. **Usage:**
   - Left-click to set the start point and end point.
   - Left-click and drag to create barriers on the grid.
   - Right-click to remove barriers.
   - Press the SPACE key to start the A* algorithm once start and end points are set.
   - Press 'c' to clear the grid.

## Grid Visualization

- White squares represent open paths.
- Black squares represent barriers.
- Orange square represents the start point.
- Turquoise square represents the end point.
- Red squares represent the closed set during the algorithm.
- Green squares represent the open set during the algorithm.
- Purple squares represent the final path found.
