# Matrix Multiplication (C)

This C program performs matrix multiplication of two matrices.

## Description

The program prompts the user to enter the dimensions (rows and columns) of two matrices. It then checks if matrix multiplication is possible (i.e., the number of columns in the first matrix must be equal to the number of rows in the second matrix). If multiplication is possible, the program prompts the user to enter the elements of both matrices. It then performs the matrix multiplication and prints the resulting matrix.

## How to Compile and Run

1.  **Save the code:** Save the C code in a file named `matrix_multiply.c` (or any other name with a `.c` extension).

2.  **Compile:** Open a terminal or command prompt and use a C compiler (like GCC) to compile the code. Navigate to the directory where you saved the file and run the following command:

    ```bash
    gcc matrix_multiply.c -o matrix_multiply
    ```

    This will create an executable file named `matrix_multiply` (or `matrix_multiply.exe` on Windows).

3.  **Run:** Execute the compiled program by running the following command in the terminal:

    ```bash
    ./matrix_multiply  # On Linux/macOS
    matrix_multiply.exe # On Windows
    ```

4.  **Input:** The program will prompt you to enter the dimensions and elements of the matrices as described below.

## Input Format

1.  **Dimensions:** You will be asked to enter the number of rows and columns for both the first and second matrices.  Enter these as space-separated integers.
2.  **Elements:** After entering the dimensions, you will be prompted to enter the elements of each matrix, row by row.  Enter the elements of each row as space-separated integers.
