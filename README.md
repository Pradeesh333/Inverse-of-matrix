# Inverse-of-matrix

## AIM:
To write a python program to find the inverse of a matrix.
## ALGORITHM:
### Step 1:
Import Numpy module as np.

### Step 2:
Create empty lists.

### Step 3:
Get input from the user for number of rows and columns.

### Step 4:
Use nested lists to append list.

### Step 5:
Print the inverse of the array using np.linalg.inv

## PROGRAM:
```
#To find the inverse of a matrix
#Developed By: Pradeesh S
#Register Number: 212221240038
import numpy as np
n=int(input())   #rows
m=int(input())   #col
mat=[]
for i in range(n):
    l1=[]
    for j in range(m):
        l1.append(int(input()))
    mat.append(l1)
print(mat)
print(np.linalg.inv(mat))
```
## OUTPUT:
![](out.jpg)
## RESULT:
Thus a program is written to find the inverse of the matrix.