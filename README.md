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

## Prerequisites
1. [Python 3](https://www.python.org/downloads/)
2. To verify python version run the next command in your terminal
```commandline
python --version
```
You should see something like this
```commandline
Python 3.8.3
```

## The current status of the game
Right now the current status is not yet completed, the UI is not ready, we have to press some keys to manipulate the game.

1. Install [PyGame](https://www.pygame.org/wiki/GettingStarted), run the next in your terminal
```commandline
python -m pip install -U pygame --user
```

2. Run the Game, run the next command in your terminal to use default values
```commandline
python -m mx.gigabyte.labs.maze.MazeGame
```

3. Run the next command to show options
```commandline
python -m mx.gigabyte.labs.maze.MazeGame -h
```
You should see something like this
```commandline
pygame 2.0.0 (SDL 2.0.12, python 3.8.3)
Hello from the pygame community. https://www.pygame.org/contribute.html
usage: MazeGame.py [-h] [--margin MARGIN] [--screen-width SCREEN_WIDTH] [--screen-height SCREEN_HEIGHT] [--cell-size CELL_SIZE] [--delay DELAY]

Maze Generator CLI Tool

optional arguments:
  -h, --help            show this help message and exit
  --margin MARGIN       Margin in the main window
  --screen-width SCREEN_WIDTH
                        The width size of the main window
  --screen-height SCREEN_HEIGHT
                        The width size of the main window
  --cell-size CELL_SIZE
                        The width size of the main window
  --delay DELAY         Delay when painting the final route from beginning to destination
```

### Using custom arguments
To pass arguments to the program use the next command
```commandline
python -m mx.gigabyte.labs.maze.MazeGame --margin=5 --screen-width=1200 --screen-height=900 --cell-size=10 --delay=2
```
this command will generate a game window with the next characteristics
- Screen width size of 1200
- Screen height size of 900
- Margin of 5
- Cell size of 10 pixels per side
- Delay of 2 ms when solving the maze and draw the final route

### Steps to manipulate the game

To manipulate the game follow the next steps
1. Click on two cells you should see two red cells
2. Press D for selecting DFS or B for selecting BFS
3. Press G for generating the maze 
   - You can again select (D)FS or (B)FS
4. Press S to solve the maze

