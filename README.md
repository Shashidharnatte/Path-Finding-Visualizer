# Path-Finding-Visualizer
# (A REACT APPLICATION)

### Check out live [HERE](https://scintillating-pixie-097c98.netlify.app/)

## Overview: 
This is a project based on visualizing path finding algorithms such as BFS, DFS, Dikstra’s , A* algorithm.
This app is totally created in react, and the interface is seen below:
Green box is the starting node and Red box is the end node.
You can see the various algorithms below to visualize.
Here design of grid is done using tables and set first node and second node colors using CSS properties.

![grid](https://github.com/Shashidharnatte/PathFinding-Visualizer/blob/main/Photos/Grid.png)


## Introduction

Path finding algorithms plays a vital role in our daily life such as packets in computer networks , google maps uses a path finding algorthm to find the shortest path.
So this project main idea is to visualize this path finding algorthms using react with the help of some css animations.

Let's check out some intuition behind this algorithms for better insights.
### Breadth First Search
* Breadth First Search explores equally in all directions.
* This is an incredibly useful algorithm, not only for regular traversal, but also for procedural map generation, flow field pathfinding, distance maps, and other types of map analysis.
* This may be the algorithm of choice to identify nearby places of interest in GPS.
* BFS guarantees the shortest path.
Below is the result for Breadth first search:
![bfs](https://github.com/Shashidharnatte/PathFinding-Visualizer/blob/main/Photos/Breadth%20first%20search.png)

### Depth First Search
- Traverses by exploring as far as possible down each path before backtracking.
- As useful as the BFS: DFS can be used to generate a topological ordering, to generate mazes, to traverse trees, to build decision trees, to discover a solution path with hierarchical choices…
- DFS does not guarantee the shortest path.
Below is the result for Depth first search:
![dfs](https://github.com/Shashidharnatte/PathFinding-Visualizer/blob/main/Photos/Depth%20first%20search.png)

### Dijkstra
- Dijkstra's Algorithm lets us prioritize which paths to explore. Instead of exploring all possible paths equally, it favors lower cost paths.
- We can assign lower cost to encourage moving on roads while assigning high cost on highway to avoid them.
- It is the algorithm of choice for finding the shortest path paths with multiple destinations.
Below is the result for Dijkstra:
![dikstra](https://github.com/Shashidharnatte/PathFinding-Visualizer/blob/main/Photos/Dijkstra's.png)

### A* (A-Star)
- A* is a modification of Dijkstra's Algorithm that is optimized for a single destination.
- Dijkstra's Algorithm can find paths to all locations; A* finds paths to one location. It prioritizes paths that seem to be leading closer to a goal.
- In a game, we could set costs to be attracted or discouraged in going near some objects : how useful it is for an AI.
- It is more or less the golden ticket or industry standard algorithm for all applications finding directions between two locations.
Below is the result for A*:
![a](https://github.com/Shashidharnatte/PathFinding-Visualizer/blob/main/Photos/A-star.png)
