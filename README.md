# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' . 
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable 
4. print the variable 'X'


## Program:
```
(i) To find the L and U matrix
```
```
/*
Program to find the L and U matrix.

Developed by: Revathi.S

RegisterNumber: 212224230228
*/
```
```
import numpy as np

from scipy.linalg import lu

A=np.array(eval(input()))

P,L,U=lu(A)

print(L)

print(U)
```
```
(ii) To find the LU Decomposition of a matrix
```
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Revathi.S
RegisterNumber: 212224230228
*/
```
```
# To print X matrix (solution to the equations)
import numpy as np

from scipy.linalg import lu_factor,lu_solve

A=np.array(eval(input()))

B=np.array(eval(input()))

lu,piv=lu_factor(A)

x=lu_solve((lu,piv),B)

print(x)
```


## Output:
![Screenshot 2025-05-19 210747](https://github.com/user-attachments/assets/9c318558-1d99-470a-96c9-89406beb699f)
![Screenshot 2025-05-19 210805](https://github.com/user-attachments/assets/a789cab3-fdc9-4801-98a8-f75263d76821)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

