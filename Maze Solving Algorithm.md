# Perfect maze or simply connected
- Mazes containing no loops are known as "simply connected", or "perfect" mazes
- Are equivalent to a tree in graph theory
- Thus many maze solving algorithms are closely related to graph theory.
# Maze Solving Algorithm
## A traveler with no prior knowledge of the maze
- The random mouse
- wall follower
- Pledge
- Trémaux's 
## A traveller can see the whole maze at once
- dead-end
- shortest path algorithms 
# Random mouse algorithm
- This is a trivial method that can be implemented by a very unintelligent robot or perhaps a mouse. 
- It is simply to proceed following the current passage until a junction is reached, and then to make a random decision about the next direction to follow. 
- Although such a method would always eventually find the right solution, this algorithm can be extremely slow.
# Wall follower
- The best-known rule for traversing mazes is the wall follower, also known as either the left-hand rule or the right-hand rule
- If the maze is simply connected, that is, all its walls are connected together or to the maze's outer boundary
    - Then by keeping one hand in contact with one wall of the maze the solver is guaranteed not to get lost and will reach a different exit if there is one; 
    - otherwise, the algorithm will return to the entrance having traversed every corridor next to that connected section of walls at least once.
# Reference
https://en.wikipedia.org/wiki/Maze_solving_algorithm