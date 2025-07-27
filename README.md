# **A\* Pathfinding Visualizer with Pyamaze**

This Python project demonstrates the **A* (A-Star) pathfinding algorithm*\* on a randomly generated maze using the `pyamaze` library. It allows you to visually see the shortest path found by the algorithm from the maze's bottom-right corner to the top-left corner.

## Features

- Generates a random NxN maze.
- Uses the A\* search algorithm to find the optimal path.
- Visualizes the solution using `pyamaze`.
- Simple CLI input to set maze size.

## Demo
- Enter the required size of the maze.
- The maze automatically opens in this way:

<img width="964" height="958" alt="image" src="https://github.com/user-attachments/assets/d07561d5-407d-4c03-9dca-17c04a922194" />

- When it has reached the goal it looks like this:

<img width="968" height="967" alt="image" src="https://github.com/user-attachments/assets/c728db6d-92d4-4f7c-aca3-4ccc83a94c43" />


## Algorithm Used

The project uses the **A* (A-Star)*\* algorithm, a popular informed search algorithm that combines the cost to reach a node (`g(n)`) and a heuristic estimate to the goal (`h(n)`) to determine the most promising path.

The heuristic used here is **Manhattan distance**.

## How It Works

1. The user inputs the size `N` of the maze.
2. The maze is generated using `pyamaze`.
3. The A\* algorithm calculates the optimal path from `(N, N)` to `(1, 1)`.
4. The path is traced and visualized using a graphical interface.

### Prerequisites

- Python 3.6+
- pip
- [pyamaze](https://pypi.org/project/pyamaze/)

## License

This project is open-source and available under the [MIT License](LICENSE).
