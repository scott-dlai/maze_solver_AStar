# A* Pathfinding Algorithm Visualizer

![Demo](./demo.png)

## Installation

### Download from Github releases

You can download the executable (binary) files directly from the
[Github's release tab.](https://github.com/scott-dlai/a-star-pathfinding/releases)

### Via source

You need to have `pip` and `python >= 3` installed

```zsh
git clone https://github.com/scott-dlai/a-star-pathfinding.git

cd a-star-pathfinding

pip install -r requirements.txt
```

Then run `python maze-solver/main.py` to run the application or use
[`pyinstaller`](https://www.pyinstaller.org) to package the project

```zsh
pyinstaller -w maze-solver/main.py
```

An executable (binary file) can be found in the `dist/` directory.

## Features

### Symbols

- `Start node` is represented by a green rectangle

- `End node` is represented by a red rectangle

- `Walls` are represented by dark blue rectangles

- `Visited nodes` are represented by light blue rectangles

- `Path nodes` are represented by yellow rectangles

### Creating a maze

- You can drag the `start node` and `end node` to move them around the grid

- You can toggle the `walls` by clicking on the `nodes`

- You can hold down the cursor and drag the mouse to draw `walls` quickly

- You can hold down the cursor and drag the mouse and hold down `alt` (`option`
key on Mac) to clear the `walls`

- You can let the computer generates a maze using the `recursive division method`
by clicking the `green button`

### Solving the maze

- Clicked on the `blue button` on the top to start running the A* algorithm on
your grid

- After the algorithm finished, you can also move the `start node` and `end node` around

### Clearing the maze

- Clicked on the `red button` on the top to clear the grid
