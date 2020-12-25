# Pacman's Search Agent

Semestrial work of a course Artificial Inteligence (4IZ431) at Prague University of Economics and Business.

We have to choose two algorithms from [AI Berkeley Pacman's project](http://ai.berkeley.edu/project_overview.html) and implement them.

I chose DFS (Depth First Search) and BFS (Breadth First Search) algorithms in [P1 - Search section](http://ai.berkeley.edu/search.html).

## DFS vs BFS

DFS is implemented in recursive way.

BFS is implemented in iterative way.

### Small Maze

|                | DFS | BFS |
| -------------- | --- | --- |
| Total Cost     | 37  | 19  |
| Nodes Expanded | 93  | 92  |
| Game score     | 473 | 491 |

### Medium Maze

|                | DFS | BFS |
| -------------- | --- | --- |
| Total Cost     | 246 | 68  |
| Nodes Expanded | 269 | 269 |
| Game score     | 264 | 442 |

### Big Maze

|                | DFS | BFS |
| -------------- | --- | --- |
| Total Cost     | 210 | 210 |
| Nodes Expanded | 466 | 620 |
| Game score     | 300 | 300 |

**In overall BFS returns better cost/scoring results than DFS.**

Since cost of each action in this Search example is 1, BFS will find optimal solution. But DFS only a "leftmost" solution.

In Big Maze is accidentally DFS's solution also an optimal.
