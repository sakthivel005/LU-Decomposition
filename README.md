# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation

2. Prepare the lists from each linear equations and assign in np.array()

3. Using the lu() function in scipy.linalg module, we can find the solutions.

4. End the program


## Program:

(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: SAKTHIVEL R
RegisterNumber: 22009121
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: SAKTHIVEL R
RegisterNumber: 22009121
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)


```

## Output:
(i)
![Screenshot from 2023-01-11 23-26-44](https://user-images.githubusercontent.com/120550359/211882317-2538284e-2926-45b8-bf9e-054c34bb5938.png)

 
 (ii)
 
 ![Screenshot from 2023-01-11 23-27-16](https://user-images.githubusercontent.com/120550359/211882251-c4a107eb-32ad-41de-9c75-64a288a8fa0e.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

