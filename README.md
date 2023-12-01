# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy package import lu
3. get input from the user 
4. print result

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:A.LAHARI 
RegisterNumber: 23002931
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
Developed by: 
RegisterNumber: 
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

![image](https://github.com/AnnaLahari/LU-Decomposition/assets/149365425/da3ee924-0bff-4a08-a976-29c8bfee6417)

![image](https://github.com/AnnaLahari/LU-Decomposition/assets/149365425/569b125c-6999-4c3d-a8e7-23e051f29e3b)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

