# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step 1:
Import the numpy module to use the built-in functions for calculations
## Step 2:
Prepare the lists from matrix and assign in np.array()
## Step 3:
Using the lu(A),we can find the solution
## Step 4:
Use the lu_solve,we can find the solution
## Step 5:
End the program
 
 

## Program:
(i) To find the L and U matrix


Program to find the L and U matrix.
Developed by:A.Aira Dario 
RegisterNumber: 25016155
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix


Program to find the LU Decomposition of a matrix.
Developed by: A.Aira Dario
RegisterNumber: 25016155

```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
X=lu_solve((lu,pivot),B)
print(X)
```


## Output:
<img width="1920" height="1080" alt="Screenshot (62)" src="https://github.com/user-attachments/assets/594ecd46-b11d-4785-8f77-269a0a650b6f" />
<img width="1920" height="1080" alt="Screenshot (63)" src="https://github.com/user-attachments/assets/176fd6a4-6cf5-430f-87f4-46bc4662c2b0" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

