EX: 9.1 MATRIX OPERATIONS
Aim: To Write a Python Program to add two matrices by reading the matrix from the user.
Algorithm:
STEP 1: Start.

STEP 2: Create a variable r and c for rows and columns of the matrix.

STEP 3: Get the value of r and c from user.

STEP 4: Define a function to create a matrix.

STEP 5 : Define another function to subtract the matrices.

STEP 6: Print the result.

STEP 7 : Stop.

Program:
def create_matrix(n,m):
         M = []
         for i in range(n):
                   row = []
                   for j in range(m):
                      x = int(input())
                       row.append(x)
           M.append(row)
         return M
r,c = input().split()
A = create_matrix(int(r),int(c))
B = create_matrix(int(r),int(c))
C = []
for i in range(int(r)):
         R = []
        for j in range(int(c)):
                item = A[i][j]+B[i][j]
        R.append(item)
C.append(R)
print(A)
print(B)
print(C)

OUTPUT:
![im1](https://github.com/user-attachments/assets/1ea3eb2c-249b-489f-b255-0784e2c03b08)

Result: Thus, the given program is implemented and executed successfully .
