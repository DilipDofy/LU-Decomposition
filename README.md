# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step 1:
We have to initialise program using import numpy to perform mathematical calculation

### Step 2:
The input from the user is stored in the variable A.

### Step 3:
from scipy.linalg import lu_factor,lu_solve and lu.

### Step 4:
Execute the program.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: DILIP M P
RegisterNumber: 212223230048
'''
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
pivot,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```

(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: DILIP MP
RegisterNumber: 212223230048
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
#### To print L and U matrix
![math ex-05 1](https://github.com/DilipDofy/LU-Decomposition/assets/147223497/04253b6c-b6d5-4f79-8cb4-f7e138789d3c)

#### To print X matrix (solution to the equations)
![math ex-05 2](https://github.com/DilipDofy/LU-Decomposition/assets/147223497/3d6d0aad-682c-4db6-893f-d6cd8e57470a)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

