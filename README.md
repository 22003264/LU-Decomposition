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
![image](https://user-images.githubusercontent.com/119389139/213916890-5d398eef-0708-46d1-a8ff-986237b1f847.png)

![image](https://user-images.githubusercontent.com/119389139/213921557-6e83c4f9-9499-408b-80c5-5bfa00586b18.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

