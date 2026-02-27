# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Perform LU decomposition using lu() or solve equations using lu_factor() and lu_solve().
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: GANESH.C
RegisterNumber: 21222525230071
*/
```
```
import numpy  as np
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
Developed by: GANESH.C
RegisterNumber: 212225230071
*/
```
```
import numpy  as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```

## Output:
<img width="1878" height="965" alt="437665188-8f776848-dea5-4201-8081-c573fdec008b" src="https://github.com/user-attachments/assets/e01762c5-0ba0-49c8-8aab-d0c0c4834028" />

<img width="1493" height="890" alt="437665222-0bdd1575-55ea-44ac-bace-14ded0ec5511" src="https://github.com/user-attachments/assets/8ed8eeac-c475-48d7-b3aa-702bda858330" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

