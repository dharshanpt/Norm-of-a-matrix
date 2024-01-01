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
# Register No:23005803
# Developed By:DHARSHAN PT
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix


import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-01-01 234111](https://github.com/dharshanpt/Norm-of-a-matrix/assets/138849376/72400aa0-4465-434d-ae2e-2cab03ec061b)


### 2-Norm of a Matrix
![Screenshot 2024-01-01 234123](https://github.com/dharshanpt/Norm-of-a-matrix/assets/138849376/bcc4b889-3d83-4bb4-afa1-ec676cd31354)

### Infinity Norm of a Matrix

![Screenshot 2024-01-01 234133](https://github.com/dharshanpt/Norm-of-a-matrix/assets/138849376/8be5a3be-cfc1-4c08-9cf1-66acd64b7428)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
