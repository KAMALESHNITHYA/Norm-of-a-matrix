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
### 1-Norm of a Matrix
```
# Register No:KAMALESH.R
# Developed By:212223230094

# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)

```
### 2-Norm of a Matrix
```

# Register No:KAMALESH.R
# Developed By:212223230094

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)
```
### Infinity Norm of a Matrix
```
Register No:KAMALESH.R
Developed By:212223230094

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(ans)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-04-23 221149](https://github.com/KAMALESHNITHYA/Norm-of-a-matrix/assets/145743119/dcef92d6-d0f5-4733-9f41-626880a81c41)

### 2-Norm of a Matrix
![Screenshot 2024-04-23 221203](https://github.com/KAMALESHNITHYA/Norm-of-a-matrix/assets/145743119/cf018ca7-b648-4827-b970-565d94aa04d4)

### Infinity Norm of a Matrix
![Screenshot 2024-04-23 221211](https://github.com/KAMALESHNITHYA/Norm-of-a-matrix/assets/145743119/0885dad5-01fd-4ea7-87ca-844a58def2bb)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
