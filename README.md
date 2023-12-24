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
# Register No: 23004033
# Developed By: PULI NAGA NEERAJ
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/PuliNagaNeeraj/Norm-of-a-matrix/assets/138849173/c9e4f854-68d1-4a4b-aa04-309e53f586a4)

### 2-Norm of a Matrix
![image](https://github.com/PuliNagaNeeraj/Norm-of-a-matrix/assets/138849173/93665579-894d-4dd0-93dd-0df40821d386)

### Infinity Norm of a Matrix
![image](https://github.com/PuliNagaNeeraj/Norm-of-a-matrix/assets/138849173/6eb8c9ab-192c-4aea-9ba8-5ceadb02e7f4)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
