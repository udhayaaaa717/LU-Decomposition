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
Program to find the L and U matrix.
Developed by: Udhaya dharshini.T
RegisterNumber: 212225230288
*/
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Udhaya dharshini.T
RegisterNumber:212225230288 
*/
```
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)

## Output:
<img width="1920" height="1150" alt="Screenshot 2026-02-07 085220" src="https://github.com/user-attachments/assets/1173a332-7b5d-4a0b-9093-639b58df86ff" />
<img width="1920" height="1150" alt="Screenshot 2026-02-07 085231" src="https://github.com/user-attachments/assets/f41eb657-f00b-4a68-b85e-a36a8db879d3" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

