# Sudoku_Solver  
A simple sudoku solver code using bit masks  
The code follows the below approach:  
* Create 3 arrays of size N (one for rows, columns, and boxes).  
* The boxes are indexed from 0 to 8. (in order to find the box index of an element we use the following formula: row / 3 * 3 + column / 3).  
* Map the initial values of the grid first.  
* Each time we add/remove an element to/from the grid set the bit to 1/0 to the corresponding bitmasks.
