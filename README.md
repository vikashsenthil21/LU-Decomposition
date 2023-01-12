# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Step 1:
Import the numpy module to use the built-in functions for calculation
2. Step 2:
Prepare the lists from each linear equations and assign in np.array()
3. Step 3:
Using the np.linalg.solve(), we can find the solutions.
4. Step 4:
End the program

## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.
Developed by: Vikash s
RegisterNumber: 22008879
import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)


```
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: Vikash s
RegisterNumber: 22008879
import numpy as np
from scipy.linalg  import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:
![lu](https://user-images.githubusercontent.com/119433834/212012319-3c9fdab5-32f0-42bf-8f90-997695741b54.png)

![lu decomposition](https://user-images.githubusercontent.com/119433834/212012536-70936b12-e26a-41c8-aef3-5a28fa66f5b7.png)


## Result:
Thus the LU Decomposition for the given matrix is successfully solved by using a python program

