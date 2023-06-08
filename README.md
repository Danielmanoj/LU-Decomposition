# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1: Import numpy library using import statement.

Step 2: From scipy package import lu().

Step 3: Get input from user and pass it as an array.

Step 4: Get P, L, U matrix using lu()

Step 5: Print L and U matrix

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: MANOJ G
RegisterNumber: 212222240060

import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: MANOJ G
RegisterNumber: 212222240060


import numpy as np
from scipy.linalg import lu_factor,lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(a)
x = lu_solve((lu,piv),b)
print(x)

```

## Output:
## To find the L and U matrix

![image](https://github.com/Danielmanoj/LU-Decomposition/assets/69635071/ff16d25a-243e-4c68-b27d-f16014f129a9)

## To find the LU Decomposition of a matrix

![image](https://github.com/Danielmanoj/LU-Decomposition/assets/69635071/2f06c2ab-f756-4783-9323-d5b5d14cb61b)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

