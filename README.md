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
# Register No: CHITHRADHEEP R
# Developed By: 2305002003
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
![image](https://github.com/Chithradheep/Norm-of-a-matrix/assets/155504933/cda239ff-65ae-4436-b3ad-26beb185e1d6)

### 2-Norm of a Matrix:
![image](https://github.com/Chithradheep/Norm-of-a-matrix/assets/155504933/e5c811db-82b4-4c2e-93ee-f5de2bc99d15)

### Infinity Norm of a Matrix:
![image](https://github.com/Chithradheep/Norm-of-a-matrix/assets/155504933/b68119e4-acb5-4d01-8622-47cc4fa5a68e)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
