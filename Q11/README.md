Title

Finding Paths to Move a Ball Out of a Grid in Exactly N Steps

Aim

To find the number of ways to move a ball outside an m × n grid in exactly N steps.

Algorithm
If the ball moves outside the grid, return 1.
If no steps remain, return 0.
From the current cell, move in four directions:
Up
Down
Left
Right
Recursively compute the number of paths.
Store intermediate results using dynamic programming (memoization).

Time Complexity

O(m × n × N)

Space Complexity

O(m × n × N)

Result

The program successfully computes the number of ways to move the ball out of the grid using dynamic programming.
