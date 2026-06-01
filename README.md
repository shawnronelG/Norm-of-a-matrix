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
```
# Register No: 212225240145
# Developed By: G.Shawn Ronel
# 1-Norm of a Matrix

'''Program to find 1-Norm of a matrix
   Developed by :G. Shawn Ronel
   Register no:25005544'''

import os
os.environ["OPENBLAS_NUM_THREADS"]='1'
import numpy as np
Inarray=np.array(eval(input()))
OneNorm=np.linalg.norm(Inarray,1)
print(OneNorm)


# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]='1'
import numpy as np
Inarray=np.array(eval(input()))
TwoNorm=np.linalg.norm(Inarray,2)
print(f"{TwoNorm:.2f}")


# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]='1'
import numpy as np
Inarray=np.array(eval(input()))
InfNorm=np.linalg.norm(Inarray,np.inf)
print(InfNorm)



```
## Output:
### 1-Norm of a Matrix
<img width="1410" height="837" alt="image" src="https://github.com/user-attachments/assets/ddf2a7fc-a764-4c26-b31d-64b4838cd282" />


### 2-Norm of a Matrix
<img width="1436" height="862" alt="image" src="https://github.com/user-attachments/assets/d047eff2-7930-4fe8-81e6-3e7b22b9d55d" />


### Infinity Norm of a Matrix
<img width="1442" height="780" alt="image" src="https://github.com/user-attachments/assets/d37a1ce0-85c4-47a8-9420-6946486fb1aa" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
