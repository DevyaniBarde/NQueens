# NQueens

## Problem Statement

This problem is to find an arrangement of N queens on a chess board, such that no queen can
attack any other queens on the board. The chess queens can attack in any direction as
horizontal, vertical, horizontal and diagonal way. That means no two queens can be placed
in same row, same column or diagonal to each other.

The problem starts with randomly placing N number of queens on a NxN chess board. The
problem is solved when all the queens are placed such that no two queens attack each other.

## Approach
### Hill Climbing

It is an iterative algorithm that starts with an arbitrary solution to a problem, then attempts
to find a better solution by making an incremental change to the solution. Hill climbing
algorithm is a local search algorithm which continuously moves in the direction of increasing
elevation/value to find the peak of the mountain or best solution to the problem. It
terminates when it reaches a peak value where no neighbor has a higher value.

 heuristic used is number of pairs of queens attacking each other.
 
