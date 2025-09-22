# Experiment 8

Name: Prathyush Nimmagadda
PRN: 24070123064
Class: ENTC A3

Title: Multidimensional Arrays
Introduction to 2D Arrays (Multidimensional Arrays)

A 2D array is essentially an array of arrays, commonly used to represent tables or matrices with rows and columns. It stores elements in a grid-like format, where each entry can be accessed using two indices — one for the row and another for the column.

Key Points:

Declaration: int arr[rows][cols];

Accessing an element: arr[i][j]

Applications: Matrix operations such as addition, multiplication, transpose, and diagonal summation.

Programs, Algorithms, and Explanation
1. Taking and Displaying a Fixed Size (3×3) Matrix

Problem: Input and display a 3×3 matrix.

Algorithm:

Define a 3×3 matrix.

Input elements into the matrix.

Display the elements in row-column form.

Explanation:
This is a basic program for practicing input and output of a fixed-size 2D array.

2. Matrix Addition

Problem: Add two matrices of the same dimensions.

Algorithm:

Input dimensions of both matrices (should match).

Input all elements of both matrices.

Initialize a result matrix.

Add corresponding elements of the two matrices.

Display the resulting matrix.

Explanation:
Addition of matrices is performed element by element, requiring equal dimensions for both.

3. Matrix Multiplication

Problem: Multiply two matrices (possible only if columns of first = rows of second).

Algorithm:

Input rows and columns of both matrices.

Verify multiplication condition (cols1 == rows2).

Input elements of both matrices.

Initialize result matrix to zero.

For each result element, calculate sum of row-by-column products.

Display the result matrix.

Explanation:
Matrix multiplication combines rows of the first matrix with columns of the second, producing a new matrix.

4. Matrix Transpose

Problem: Find the transpose of a matrix.

Algorithm:

Input rows and columns.

Input matrix elements.

Create transpose matrix with swapped dimensions.

For each element (i,j), assign it to transpose[j][i].

Display the transpose.

Explanation:
Transpose interchanges rows and columns, and it is widely used in algebraic computations and transformations.

5. Sum of Diagonal Elements of a Matrix

Problem: Calculate the sum of the main diagonal elements.

Algorithm:

Input number of rows and columns.

Check if matrix is square (rows == cols).

Input elements of the square matrix.

Initialize sum = 0.

Add all elements at positions (i,i) to sum.

Output the sum.

Explanation:
The main diagonal contains elements where row index equals column index (like (0,0), (1,1), (2,2)…). Adding them gives the diagonal sum.

Conclusion

These programs demonstrate the basic yet essential operations on 2D arrays in C++. Mastering such manipulations is important for solving advanced problems involving matrices, which are widely used in graphics, simulations, and data processing.
