# Maze Solver with DFS Algorithm

A Python implementation of the Depth-First Search (DFS) algorithm applied to maze solving, with graph visualization to show how the maze is represented and traversed.

## Features

- 🧩 **Custom Maze Input** - Works with any maze configuration
- 🔍 **DFS Algorithm** - Implements depth-first search with backtracking
- 📊 **Graph Visualization** - Shows the maze as a graph with nodes and edges
- 🗺️ **Solution Path** - Displays the optimal path from start to end
- 👣 **Exploration Tracking** - Shows all visited cells vs. final solution path

## How It Works

The algorithm converts a 2D maze into a graph where:
- Each walkable cell is a **node**
- Adjacent cells are connected by **edges**
- DFS explores the graph recursively, prioritizing depth over breadth

### DFS Strategy
1. Start at position S
2. Explore DOWN first, going as deep as possible
3. When blocked, backtrack and try LEFT
4. Then try RIGHT
5. Finally try UP
6. Repeat until reaching E (end)

## Visualization Legend

- `S` = Start position
- `E` = End position
- `#` = Walls
- `*` = Solution path
- `.` = Visited cells (explored but not in final solution)

## Output

The program displays:
1. Original maze layout
2. Graph representation (adjacency list)
3. Solved maze with solution path
4. Statistics (path length, cells visited)
5. Step-by-step coordinates

## Requirements

- Python 3.x
- No external dependencies
  
## Learning Goals

- Understand DFS algorithm and backtracking
- Visualize how graphs represent spatial problems
- See the difference between explored cells and solution path
- Learn recursive problem-solving techniques
