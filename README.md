# Maze Generator with Python

## Description
This is a Game developed with [PyGame](https://www.pygame.org/), the main objective is to visualize two algorithms for searching
in GRAPH problems:
- [Breadth-first search](https://en.wikipedia.org/wiki/Breadth-first_search)
- [Depth-first search](https://en.wikipedia.org/wiki/Depth-first_search)

The Game will generate and solve the maze using one of these algorithms. These means that
- We can generate the MAZE using BFS and solve it using BFS
- We can generate the MAZE using BFS and solve it using DFS
- We can generate the MAZE using DFS and solve it using BFS
- We can generate the MAZE using DFS and solve it using DFS

## The current status of the game
Right now the current status is not yet completed, the UI is not ready, we have to press some keys to manipulate the game.

1. Install [PyGame](https://www.pygame.org/wiki/GettingStarted), run the next in your terminal
```commandline
python3 -m pip install -U pygame --user
```

2. Run the Game, run the next command in your terminal
```
~/Documents/proyectos/python/MazeGenerator> python3 -m mx.gigabyte.labs.maze.MazeGame
```

### Steps to manipulate the game

To manipulate the game follow the next steps
1. Click on two cells you should see two red cells
2. Press D for selecting DFS or B for selecting BFS
3. Press G for generating the maze 
   - You can again select (D)FS or (B)FS
4. Press S to solve the maze

