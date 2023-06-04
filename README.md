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
# Register No: 212222240048
# Developed By: KEERTHI VASAN A
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
norm = np.linalg.norm(mat,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
norm = np.linalg.norm(mat,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
infinity = np.linalg.norm(mat,np.inf)
print("{:.2f}".format(infinity))
```
## Output:
### 1-Norm of a Matrix

![Screenshot (167)](https://github.com/Keerthi-Vasan-Adhithan/Norm-of-a-matrix/assets/107488929/9c8a6bd1-33e0-43a5-8bbf-afbc8ed00166)

### 2-Norm of a Matrix

![Screenshot (168)](https://github.com/Keerthi-Vasan-Adhithan/Norm-of-a-matrix/assets/107488929/b5866abb-40f8-4fff-b4f9-4813c65550df)

### Infinity Norm of a Matrix

![Screenshot (169)](https://github.com/Keerthi-Vasan-Adhithan/Norm-of-a-matrix/assets/107488929/6f0006c4-bf3d-46e2-a818-e93ad7531894)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
