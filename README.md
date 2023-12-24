# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy
2. from scipy.linlag import lu,lu_factor,lu,solve.
3. solve using scipy.linlag(variable)
4. Print the output

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: DHARSAN KUMAR R
RegisterNumber:23014208 
import numpy as nu
from scipy.linalg import lu
a=nu.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: DHARSAN KUMAR R
RegisterNumber: 23014208
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
A=np.array(a)
B=np.array(b)
result=lu_factor(A)
sol=lu_solve(result,B)
print(sol)
```
## Output:
![image](https://github.com/DHARSAN23014208/LU-Decomposition/assets/149365413/085e8731-27e9-4492-9d38-a8367d224d3a)
![image](https://github.com/DHARSAN23014208/LU-Decomposition/assets/149365413/e8b8487b-5c9b-40d3-8193-f7faa16fdc67)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

