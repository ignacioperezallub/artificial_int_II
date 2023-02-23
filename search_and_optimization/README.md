# Assignment no° 1 : Search and Optimization
## Mandatory Exercises:
1. Given a warehouse with a layout similar to the following, calculate the shortest path (and distance) between 2 positions in the warehouse, given the coordinates of these positions, using the A* algorithm.

2. Given an order, which includes a list of products from the previous warehouse that must be dispatched in full, determine the optimal order for the picking operation using Simulated Annealing. What other algorithms can be used for this task?

3. Implement a genetic algorithm to solve the problem of optimizing the location of products in the warehouse, in order to optimize their picking. Consider that:
* The layout of the warehouse is fixed (size and location of aisles and shelves), only the location of the products must be determined.
* Each order includes a set of products that must be dispatched in full.
* The picking starts and ends at a loading bay, which has certain coordinates in the warehouse (for generality, the loading bay can be considered on any edge of the warehouse).
* The "cost" of picking is proportional to the distance traveled.

Optional Exercises:

4. Given a point in the joint space of a 6 degree-of-freedom serial robot, find the shortest path to reach another point using the A* algorithm. Randomly generate start and end points, as well as obstacles that the robot must avoid, always in joint space.

5. Implement a constraint satisfaction algorithm to solve a scheduling problem. The scheduling problem consists of assigning resources to tasks. Model the variables, domain of the variables, constraints, etc. Assume that:
* There is a certain number of tasks that must be performed.
* Each task requires a specific machine (not all machines are of the same type).
* Each task has a specific duration.
* There is a certain (limited) number of machines of each type (there can be more than one machine of each type).
* The capacity of each machine at a given time cannot be exceeded: a machine can only perform one task at a given time.
