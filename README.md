## CSMM_101X_SUDOKU_SOLVER

Enter into unix command line the following prompt:

> Python driver.py **sudoku_string**

The **sudoku_string** is an 81 character string representing the starting state of the board, with zeros as empty squares. For example:

> Python driver.py 000000000302540000050301070000000004409006005023054790000000050700810000080060009

This program will first attempt to solve the puzzle using the AC3 algorithm, which is much quicker. If no solution is found, then it switches over to the backtracking method. Computationally, this is more intensive but a solution will be found.

Program prints string of completed board, followed by either ACS or BTS depending on which was used to solve. The above example would print the following:

> 148697523372548961956321478567983214419276385823154796691432857735819642284765139 BTS
