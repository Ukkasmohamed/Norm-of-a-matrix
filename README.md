# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:
# Developed By:
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
matrix = eval(input())

one_matrix = np.linalg.norm(matrix,1)
print(f"{one_matrix:.2f}")



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Mohamed Ukkas R
RegisterNumber: 212225040245
'''
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
matrix = eval(input())
two_matrix = np.linalg.norm(matrix, 2)
print(f"{two_matrix:.2f}")



# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
matrix = eval(input())
inf_matrix = np.linalg.norm(matrix,np.inf)
print(f"{inf_matrix:.2f}")



```
## Output:
### 1-Norm of a Matrix
<br>
<br><img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9c20e059-ca68-4cfd-b084-093c5948e8ec" />

<br>

### 2-Norm of a Matrix
<br>
<br><img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5fb2512b-d97f-4859-b108-020073d51a0f" />

<br>

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bdecc6b7-673c-4c7d-90a2-9b176bc08658" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
