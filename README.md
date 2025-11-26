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
# Register No: 25017992
# Developed By: Eswar S

# 1-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(norm1)

# 2-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")

# Infinity Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norminf=np.linalg.norm(A,np.inf)
print(f"{norminf:.2f}")

```
## Output:
### 1-Norm of a Matrix

<img width="1447" height="818" alt="Screenshot 2025-11-26 112317" src="https://github.com/user-attachments/assets/9e66f81f-7e4b-4e38-88d0-6cf0cbd684fd" />

### 2-Norm of a Matrix

<img width="1453" height="814" alt="Screenshot 2025-11-26 112347" src="https://github.com/user-attachments/assets/f688c92b-698a-40b5-9d27-b01d414300ba" />

### Infinity Norm of a Matrix

<img width="1450" height="783" alt="Screenshot 2025-11-26 112405" src="https://github.com/user-attachments/assets/08d472e6-697b-475e-bc45-9b1b12e7e5ef" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
