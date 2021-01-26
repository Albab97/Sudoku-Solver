Project : SUDOKU SOLVER

Backtracking : Backtracking is an algorithmic-technique for solving problems recursively by trying to build a solution incrementally, one piece at a time, removing those solutions that fail to satisfy the constraints of the problem at any point of time (by time, here, is referred to the time elapsed till reaching any level of the search tree).

Objective : To make a N x N Sudoku Solver.

Pre-requisite Knowledge : Recursion and Backtracking Algorithm.

Theory : 
In this project, we are going to implement a C++ program which solves Sudoku puzzles for us. Below is brief description of Sudoku and its rules:
Sudoku is a logic puzzle. The objective is to fill a 9×9 grid with digits in such a way such that each column, each row, and each of the nine 3×3 grids that make up the larger 9×9 grid contains all of the digits from 1 to 9 exactly once.
Each Sudoku puzzle begins with some cells filled in. These numbers are chosen such that there is a unique solution to the Sudoku.

Problem : We are given an N*N sudoku grid (N is a multiple of 3). Solve the sudoku and print the solution.

Input Format : First line contains a single integer N. Next N lines contains N integers each, where jth integer int ith line denotes the value at ith row and jth column in sudoku grid. This value is 0, if the cell is empty.

Output Format : Print N lines containing N integers each, where jth integer int ith line denotes the value at ith row and jth column in sudoku grid, such that all cells are filled.
