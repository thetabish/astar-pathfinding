# astar-pathfinding
This program implements the A* pathfinding algorithm using the pygame library


1. The player can set start and end points on the grid that appears by clicking on the desired points. And then the walls can be set up between these points anywhere
   on the grid.

2. Once the points and walls are set, the program starts the A* algorithm when the spacebar is pressed. The program starts the traversal from the start point while
   avoiding the walls. The tried paths appear in red.

3. When the program reaches the end point, the final shortest path is drawn.

4. This program demonstrates the working of the A* algorithm, which is used in many fields of computer science due to its completeness, optimality, and efficiency.
   This algorithm is essentially an extension of the Dijkstra's algorithm, with an addition of an heuristic function. 
   
5. The heuristic function provides an estimate of the minimum cost between a given node and the target node. The algorithm will combine the actual cost from the start node - referred to as g(n) - with the estimated cost to the target node - referred to as h(n) - and uses the result to select the next node to evaluate.
