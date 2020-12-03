# Problem Statement

You are given a Grid (matrix) of N x M, where N,M >=1

Each cell in the matrix has a non-negative value denoting the cost of traversing that cell.

Initially you are at the position [1,1]. You have to reach to the cell [N,M] at minimum cost. You are only allowed to move 1 cell right or 1 cell down at a time.

## Example

Suppose we have the following grid of 6 x 7

![loading](/grid1.png)

Starting from the cell [1,1], you have to reach to the cell [6,7] at minimum cost.

## Solution

The most intuitive solution is to look at the cell below you and the cell right to you, and choose the one with the shorter value. Repeat this process till you reach the destination.

Let us follow this strategy -

![loading](/grid4.png)

The cost of reaching the destination using this path is- 66

Are there any better paths? 

Yes, I found one whose cost is only 54 -

![loading](/grid2.png)

Check out this link to find the correct solution-

