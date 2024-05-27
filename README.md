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
# Register No: MADHUMITHA V
# Developed By: 2305002013
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix:
![image](https://github.com/Madhumitha2006/Norm-of-a-matrix/assets/155504933/926fcbf7-d91b-4a45-9fd8-76c1192dcaaf)

### 2-Norm of a Matrix:
![image](https://github.com/Madhumitha2006/Norm-of-a-matrix/assets/155504933/d05cb661-2e1a-4d8d-ac57-de37f8ed27ec)

### Infinity Norm of a Matrix:
![image](https://github.com/Madhumitha2006/Norm-of-a-matrix/assets/155504933/854f53a1-d6e8-4910-a915-da8d7d856446)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
