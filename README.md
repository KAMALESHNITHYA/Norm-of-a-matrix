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
### 1.NORM OF A MATRIX
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
### 2.NORM OF A MATRIX
```
Register No:KAMALESH.R
Developed By:212223230094

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)
```
### 3.INFINITY NORM OF A MATRIX
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
![Screenshot 2024-04-23 221149](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/145743119/ef7b3c09-810c-4879-a47e-0843fcdde24f)

### 2-Norm of a Matrix
![Screenshot 2024-04-23 221203](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/145743119/ab4889df-a757-41b1-bc90-c65bf2b658bd)

### Infinity Norm of a Matrix
![Screenshot 2024-04-23 221211](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/145743119/235254c3-396c-4951-9fe4-26407f2ee10b)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
