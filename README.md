# Knapsack_D_Wave
Knapsack
Consider a problem found in packing shipping containers on docks. There is a collection of objects; each object has a value, and a weight. The shipping container has a weight capacity which it can hold. The goal is to pack the shipping container in order to:

maximize the sum total of the values of the objects put into the container.
fill up the container so that the total weight is less than or equal to the container's capacity.
This well-known optimization problem is known as the knapsack problem. To solve this problem on a D-Wave system, we reformulate it as a quadratic unconstrained binary optimization problem (QUBO).

Usage
To run a small demo, run the command:
python knapsack.py data/small.csv 50

