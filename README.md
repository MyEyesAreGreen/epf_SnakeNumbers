# epf_SnakeNumbers
External processing that fills the table of values with descending numbers in a clockwise spiral

The algorithm for generating a numerical "snake": the initial data is only the length of the side of the final matrix.
Examples:
- for the entered number 3, the result should look something like this:
[9][8][7]
[2][1][6]
[3][4][5]

- for the number 5, the matrix is:
[25][24][23][22][21]
[10] [9] [8] [7][20]
[11] [2] [1] [6][19]
[12] [3] [4] [5][18]
[13][14][15][16][17]

The result should be presented as an external processing, where there will be a field for entering a number (from 1 to 16), a command for forming a "snake" and fields for displaying the result.
That is, we start with the largest number and spiral to the center clockwise.
