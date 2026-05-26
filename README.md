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
'''
Program to find the 1-Norm of a matrix.
Developed by: ANNLEE AGHAI DAVIDSON
RegisterNumber: 212225040023
'''

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

# Input matrix
A = np.array(eval(input()))

# Calculate 1-Norm
norm1 = np.linalg.norm(A, 1)

# Display result
print(f"{norm1:.2f}")




# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

# Input matrix
A = np.array(eval(input()))

# Calculate L2-Norm
l2_norm = np.linalg.norm(A, 2)

# Display result
print(f"{l2_norm:.2f}")


# Infinity Norm of a Matrix


import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

# Input matrix
A = np.array(eval(input()))

# Calculate Infinity Norm
inf_norm = np.linalg.norm(A, np.inf)

# Display result
print(f"{inf_norm:.2f}")


```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br><img width="760" height="831" alt="image" src="https://github.com/user-attachments/assets/f4312ba8-cf61-4c4b-b002-3ce618bd13d0" />




### 2-Norm of a Matrix
<br>
<br>
<br><img width="717" height="857" alt="image" src="https://github.com/user-attachments/assets/9259bf91-cfea-42b8-99b9-459c1d5da72c" />


### Infinity Norm of a Matrix
<br>
<br>
<br><img width="847" height="862" alt="image" src="https://github.com/user-attachments/assets/2cd3e2b8-d5f3-4a85-887a-7794e1fca937" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
