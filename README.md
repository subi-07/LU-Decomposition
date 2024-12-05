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

```
/*
(i)Program to find L and U matrix using LU decomposition.
Developed by: SUBITHRA R
RegisterNumber:24900702 


import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)

*/
```
(ii)
*/
```Program to solve a matrix using LU decomposition.
Developed by: SUBITHRA R
RegisterNumber: 24900702


import numpy as np
from scipy.linalg import lu_factor,lu_solve
lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
*/
```
## Output:
![lu decomposition]()
![alt text](<maths  ex 5.jpg>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

