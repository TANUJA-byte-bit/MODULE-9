# 9b)  List Comprehension:Transpose of Matrix 

##  AIM:
To write a Python program to compute the **transpose** of a matrix using **list comprehension**.

---

##  ALGORITHM:

1. **Start**
2. Create variables `r` and `c` to represent the number of rows and columns of the matrix.
3. Get the values of `r` and `c` from the user.
4. Define a function `create(r, c)` to create the matrix by reading the elements from the user.
5. Use **list comprehension** to calculate the transpose of the matrix.
6. Print the transposed matrix.
7. **Stop**

---

##  PROGRAM:
```
def read_matrix(r,c):
    matrix=[[0]*c for i in range(r)]
    for i in range(r):
        line=list(map(int,input().split()))
        for j in range(c):
            matrix[i][j]=line[j]
    return matrix
def print_matrix(M):
    print("Matrix:")
    for i in range(len(M)):
        for j in range(len(M[0])):
            print(M[i][j],end=" ")
        print()
def transpose(M):
    result=[[0]*len(M) for i in range(len(M[0]))]
    for i in range(len(M)):
        for j in range(len(M[0])):
            result[j][i]=M[i][j]
    return result
```
## OUTPUT:
<img width="704" height="506" alt="image" src="https://github.com/user-attachments/assets/4457691d-8ee2-4732-ab9d-59659eea5cfd" />

## RESULT:
Program executed Successfully.

