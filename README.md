# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()
2. Find the 1,2,infinity-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```
'''
Program to find 1-norm of a matrix.
Developed by Sriharikumar k
Register Number:212225230273'''
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1" 
import numpy as np
matrix=eval(input()) 
A=np.array(matrix)
nor=np.linalg.norm(A,1) 
print(f"{nor:.2f}") 
```
# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: sriharikumar k
RegisterNumber: 212225230273
'''
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
A=np.array(matrix)
nor=np.linalg.norm(A,2)
print(f"{nor:.2f}")
```
# Infinity Norm of a Matrix

```
'''
Program to find 2-norm of a matrix.
Developed by: sriharikumar k 
RegisterNumber: 212225230273
''' 
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1" 
import numpy as np
matrix=eval(input()) 
A=np.array(matrix)
nor=np.linalg.norm(A,np.inf) 
print(f"{nor:.2f}") 
```
## Output:
### 1-Norm of a Matrix
<img width="717" height="858" alt="image" src="https://github.com/user-attachments/assets/b04cc6aa-711e-4789-b1af-5f2e6b051dd0" />

### 2-Norm of a Matrix
<img width="639" height="939" alt="image" src="https://github.com/user-attachments/assets/61bacf11-e467-4227-84a6-b90575d65ced" />

### 3-Infinity Norm of a Matrix
<img width="645" height="851" alt="image" src="https://github.com/user-attachments/assets/c84af6c0-76eb-458d-a0ec-763863ced6d7" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
