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
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu

a = np.array(eval(input()))
p,l,u = lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve

a = np.array(eval(input()))
b = np.array(eval(input()))

pv,lu = lu_factor(a)
res = lu_solve((pv,lu),b)
print(res)
```

## Output:
![image](https://github.com/user-attachments/assets/19c1f2eb-6992-47e7-affe-d6db075f3553)
![image](https://github.com/user-attachments/assets/b20adcfe-e6b8-42a3-91b8-ac6ab5c8bd17)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

