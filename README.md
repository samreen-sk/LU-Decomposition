# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np.
2. Import lu from scipy.linalg to execute the code.
3. Store the input in the variable. 
4. Write code.and print the answer using print().

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: shaik samreen
RegisterNumber: 23013412
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
## OUTPUT:
![output](./find_lu.png)
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: shaik samreen
RegisterNumber: 23013412
from scipy.linalg import lu_factor,lu_solve 
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
*/
```
## OUTPUT:
![output](./solve_lu.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

