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
'''Program to find L and U matrix using LU decomposition.
Developed by:John Paul J 
RegisterNumber:23011778
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
Developed by: John Paul J
RegisterNumber:23011778 
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
![output1](https://github.com/JOHNSUBIK/LU-Decomposition/assets/150279319/770f6907-9ed7-40bc-b889-dcfce406560a)
![output2](https://github.com/JOHNSUBIK/LU-Decomposition/assets/150279319/d560a804-c370-462e-8bb4-c546eaa61681)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

