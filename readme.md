The Sudoku Solver works by interpreting "-1" as what would be an empty slot on a normal sudoku.
To do this, the code has to do a couple of things. 
It has to define a set of functions that will interpret how the board is set up.
First, it identifies whether there is a "-1" in the space or not.
If there is another number, the code will go to the next slot and check whether there is a "-1".
This will go on until it finds a slot with a "-1".
After it finds a "-1", the code will check the numbers in the row, column, and the 3 by 3 square.
If the "guess" is not in the row, column, or 3 by 3 square, it will replace the "-1" with the "guess" value.
If the "guess" value IS already in any of those 3, "guess" will change and the code will check again for any repetition of that number.
The code will keep doing this until it reaches the end of the board, replacing every "-1" with a valid "guess".
