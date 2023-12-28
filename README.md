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
# Register No:23004739
# Developed By:VEERARAGAVAN V
# 1-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
norm=max(np.sum(abs(matrix),axis=0))
print("{:.2f}".format(norm))
# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: VEERARAGAVAN V
RegisterNumber: 23004739
'''
import numpy as np
# Type your code here
matrix=np.array(eval(input()))
norm=np.linalg.norm(matrix,ord=2)
print("{:.2f}".format(norm))
# Infinity Norm of a Matrix
import numpy as np
# Type your code here
matrix=np.array(eval(input()))
norm=np.linalg.norm(matrix,ord=np.inf)
print("{:.2f}".format(norm))
```
## Output:
### 1-Norm of a Matrix
<br>![Screenshot 2023-12-28 172233](https://github.com/veerargavanv27/Norm-of-a-matrix/assets/138955645/5a1c7a12-dad3-4ad2-956e-e8600323f1a6)
### 2-Norm of a Matrix
<br>![Screenshot 2023-12-28 172156](https://github.com/veerargavanv27/Norm-of-a-matrix/assets/138955645/2cd74bbe-56dc-4cc1-a37e-2231f4180e4a)
### Infinity Norm of a Matrix
<br>![Screenshot 2023-12-28 172113](https://github.com/veerargavanv27/Norm-of-a-matrix/assets/138955645/bcbaf652-e6ba-4a8c-aaaf-c5addb262514)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
