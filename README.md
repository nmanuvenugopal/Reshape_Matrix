# Reshape_Matrix
You are given an m x n matrix mat and two integers r and c representing the number of rows and the number of columns of the wanted reshaped matrix.  The reshaped matrix should be filled with all the elements of the original matrix in the same row-traversing order as they were.  If the reshape operation with given parameters is possible and legal, output the new reshaped matrix; Otherwise, output the original matrix.

1. Simplest method is to import numpy library.
2. numpy provide a simple method "reshape", which takes in matrix to be reshaped, shape (rows, column) the output matrix should be.
3. len(matrix) ---> means the number of rows in the matrix.
4. len(matrix[0]) ----> means the number of columns in the matrix.
5. output_rows * output_columns must be equal to len(matrix) * len(matrix[0]), then only we can convert or reshape the matrix.
6. else return the original matrix.
