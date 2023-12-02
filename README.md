# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
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
![maths ](https://github.com/23004205/LU-Decomposition/assets/138971114/95e9220c-d130-4f50-8b5d-d1170cf188f0)

![maths 22](https://github.com/23004205/LU-Decomposition/assets/138971114/44616314-4ad1-4129-a21f-6cafecfa8b37)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

