# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Start the program
Import the necessary libraries(numpy,scipy.linalg)
Define the matrix using numpy
Use lu(),lu_solve(),lu_factor() to get the solutions
End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Santhosh
RegisterNumber: 212225230250
*/
import numpy as np
from scipy.linalg import lu
InputMatrix=np.array(eval(input()),dtype='i')
piv,Lmatrix,Umatrix=lu(InputMatrix)
print(Lmatrix)
print(Umatrix)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: santhosh
RegisterNumber: 212225230250
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
AMatrix=np.array(eval(input()),dtype='i')
BMatrix=np.array(eval(input()),dtype='i')
XMatrix=lu_factor(AMatrix)
Solution=lu_solve(XMatrix,BMatrix)
print(Solution)
```

## Output:
![lu decomposition]()
<img width="898" height="772" alt="image" src="https://github.com/user-attachments/assets/23efaca1-6bb4-4570-a58c-3d37321e03c6" />
<img width="653" height="452" alt="image" src="https://github.com/user-attachments/assets/e83d1e11-ef1b-4a23-a2e9-a6a741a493a8" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

