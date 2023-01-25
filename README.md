# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library as np
2. Create a matrix using np.array()
3. Using scipy.linalg.lu() find L and U, also using scipy.linalg.lu_solve() get the result for LU Decomposition
4. Get the output and end the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Koti Sai Sankar
RegisterNumber: 22001315

import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Koti Sai Sankar
RegisterNumber: 22001315

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
*/
```

## Output:

![Screenshot from 2023-01-25 23-16-51](https://user-images.githubusercontent.com/118344248/214642001-1d1db5de-1e64-48d5-8d82-4a24c21810bc.png)

![Screenshot from 2023-01-25 23-17-25](https://user-images.githubusercontent.com/118344248/214642122-eaf0540d-3849-4531-9720-f8243b8f613a.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

