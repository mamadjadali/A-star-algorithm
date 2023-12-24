# A-star-algorithm
  visualization of the A* pathfinding algorithm using Pygame

# Installation

    pip install pygame

# Usage

Run the script main.py to launch the pathfinding algorithm visualization.
Follow the on-screen instructions:

>click to place the start and end nodes.<br>
>click on the grid to add barrier nodes.<br>
>Press the space bar to start the pathfinding algorithm.<br>
>Press 'C' to clear the grid.<br>


# Functions

**Spot**: Represents individual squares on the grid with various attributes and methods to manage their properties.<br>
**h(p1, p2)**: Computes the Manhattan distance between two points, used as the heuristic function in the A* algorithm.<br>
**draw_path**(came_from, current, draw): Draws the shortest path on the grid based on the "came_from" dictionary.<br>
**algorithm**(draw, grid, start, end): Implements the A* algorithm to find the shortest path from the start to the end node.<br>
**create_grid**(rows, width): Creates the grid by initializing a 2D array of Node objects.<br>
**draw_grid**(win, rows, width): Draws the grid lines on the screen.<br>
**draw**(win, grid, rows, width): Draws the entire grid on the screen.<br>
**get_position**(pos, rows, width): Converts mouse coordinates to grid row and column.<br>
**main**(win, width): Main function to manage user interactions, start the application, and handle input events.<br>

