# DiagonalDifference

## Description

Given a square matrix, calculate the absolute difference between the sums of its diagonals.

For example, the square matrix is shown below:
```
1 2 3
4 5 6
9 8 9  
```
The left-to-right diagonal: _1 + 5 + 9 = 15_. The right to left diagonal: _3 + 5 + 9 = 17. Their absolute difference is _|15 - 17| = 2_.

## Returns

- int: the absolute diagonal difference 

## Input Format

- The first line contains a single integer, _n_, the number of rows and columns in the square matrix _arr_.
- Each of the next _n_ lines describes a row, _arr[i]_, and consists of _n_ space-separated integers _arr[i][j]_.

