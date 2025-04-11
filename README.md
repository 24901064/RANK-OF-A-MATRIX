# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Convert the input matrix to a NumPy array with float data type.

2. Initialize rank = 0 and get the number of rows and columns of the matrix.

3. For each row i, if A[i, i] is zero, swap rows to place a non-zero element in the diagonal position.

4. If A[i, i] is non-zero, normalize row i by dividing it by A[i, i].

5. For each row j below row i, eliminate the element below the pivot by subtracting a multiple of row i from row j.

6. Count the number of non-zero rows in the resulting matrix and return the rank. 
## Program:
import numpy as np


matrix = np.array([[1, 2, 3],
                   [3, 6, 9]])


rank = np.linalg.matrix_rank(matrix)

print(f"The rank of the matrix is: {rank}")



## Output:
![Screenshot 2025-04-11 213703](https://github.com/user-attachments/assets/7e73fcab-a870-4da1-8c80-212a46f02b30)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.


