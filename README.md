# 15_Puzzle

Implement the A* Search Algorithm with Graph Search for solving the 15-
puzzle problem as described below. Use sum of chessboard distances of tiles from their goal
positions as heuristic function, where chessboard distance is defined as the maximum of the
horizontal and vertical distances. [Reminder: Graph Search does not allow repeated states.]
15-puzzle problem: On a 4 x 4 board there are 15 tiles numbered from 1 to 15 and a blank
position. A tile can slide into the blank position if it is horizontally, vertically or diagonally
adjacent to the blank position. Given a start board configuration and a goal board configuration,
find a sequence of moves to reach the goal configuration from the start configuration. The goal is
to find a solution with minimum number of moves.
To solve the puzzle problem, you can define eight virtual moves for the blank position:
1. Left
2. Up-left
3. Up
4. Up-right
5. Right
6. Down-right
7. Down
8. Down-left