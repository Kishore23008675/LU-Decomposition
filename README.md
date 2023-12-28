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
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: Kishore A
RegisterNumber:23008675
'''
from scipy.linalg import lu
import numpy as np
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
 '''Program to solve a matrix using LU decomposition.
Developed by: Kishore A
RegisterNumber:23008675
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


*/
```

## Output:
![image](https://github.com/Kishore23008675/LU-Decomposition/assets/144979375/93d42fb4-1813-4472-940d-af7884bf3ba5)
![image](https://github.com/Kishore23008675/LU-Decomposition/assets/144979375/65d83261-948b-4b45-b2f0-58fa459773ef)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

