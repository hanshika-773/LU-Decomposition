# Date:
# Ex.No 5: LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print'.
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Hanshika Varthini R
RegisterNumber: 212223240046
*/
import numpy as np
import scipy
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Hanshika Varthini R
RegisterNumber: 212223240046
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:
![lu decomposition]()
![Screenshot 2024-10-16 141901](https://github.com/user-attachments/assets/dabb363c-4e0f-4a8b-b439-8515ff00f6ea)
![Screenshot 2024-10-16 141912](https://github.com/user-attachments/assets/56800c47-864f-4ff7-b24e-34d3c89bcd76)

## Result:

Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

