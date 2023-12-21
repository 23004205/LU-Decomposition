# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import the numpy module to use the built-in functions for calculation.

2.Prepare the lists from each linear equations and assign in np.array().

3.Using the scipy.linalg and imort lu_fator and lu_solve we get the values.

4.End the program

## Program:
(i) find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: singamala venkata sai kumar reddy
RegisterNumber: 23004205
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
 '''Program to solve a matrix using LU decomposition.
Developed by: singamala venkata sai kumar reddy
RegisterNumber:23004205 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv),b)
print(x)

*/
```

## Output:
![Screenshot 2023-12-21 121100](https://github.com/23004205/LU-Decomposition/assets/138971114/9f28afc3-ff1b-49cf-8026-f62e527c402e)

![Screenshot 2023-12-21 121153](https://github.com/23004205/LU-Decomposition/assets/138971114/55edf664-7c8b-400f-a3e6-807ef8e5da45)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

