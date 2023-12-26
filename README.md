# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. define the package as scipy.linalg import lu.
2. get input from user and print L and U matrix by 'print'.
3. define a package as "from scipy.linalg  import lu_factor,ku_solve" and create the variable as 'X'
4. print the variable.


## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: SHARAN.G
RegisterNumber: 23002031
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: SHARAN.G
RegisterNumber: 23002031
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

```

## Output:
![lu decomposition]()
![image](https://github.com/Sharan1731/LU-Decomposition/assets/144980172/5040e444-2ebd-4a88-ac9c-072e1c40f9af)

![image](https://github.com/Sharan1731/LU-Decomposition/assets/144980172/54b5e80c-4824-457d-b804-bd60577c39ef)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

