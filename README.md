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
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

## Developed by: Pooja V
## Register number: 212225040302


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

## Developed by: Pooja v
## RegisterNumber: 212225040302


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

## Developed by: Pooja V
## Register number: 212225040302

```
## Output:
### 1-Norm of a Matrix
<img width="1207" height="721" alt="image" src="https://github.com/user-attachments/assets/35ac1472-d6a6-42bc-bbe6-b7cea354d9e6" />


### 2-Norm of a Matrix
<img width="1313" height="784" alt="image" src="https://github.com/user-attachments/assets/92d3b73d-b777-4f08-9f5d-292e5d56a157" />


### Infinite-Norm of a Matrix
<img width="1178" height="707" alt="image" src="https://github.com/user-attachments/assets/d6047ea8-d450-4914-ba62-cffbf4754f88" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
