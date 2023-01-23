# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.
##
Algorithm:

1.Import the numpy module to use the built-in functions for calculation.

2.Prepare the lists from each linear equations and assign in np.array().

3.Using the scipy.linalg and imort lu_fator and lu_solve we get the values.

4.End the program
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
```
'''Program to solve a matrix using LU decomposition.
Developed by: Sirisha Onteddu
RegisterNumber: 22003264
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv),b)
print(x)

```
## Output:
L and U decomposition
![image](https://user-images.githubusercontent.com/119389139/213922001-9dd4a6c2-9057-4cbe-af75-8b816acc50fe.png)

LU decomposition
![image](https://user-images.githubusercontent.com/119389139/213921955-bb7768c8-84d6-4618-886b-c271a7f0f569.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

