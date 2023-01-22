# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.
## Algorithm:

## Program:
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Sirisha Onteddu
RegisterNumber: 22003264
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
## Output:
![image](https://user-images.githubusercontent.com/119389139/213916890-5d398eef-0708-46d1-a8ff-986237b1f847.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

