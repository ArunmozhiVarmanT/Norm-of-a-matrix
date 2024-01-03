# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.Hardware – PCs
2.Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:

# 1-Norm of a Matrix
### Program to find 1-norm of a matrix.
### Developed by:ARNMOZHI VARMAN T
### Register Number: 212223230022
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```

# 2-Norm of a Matrix
```
### Program to find 2-norm of a matrix.
### Developed by:ARNMOZHI VARMAN T
### Register Number: 212223230022

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```

# Infinity Norm of a Matrix
```
### Program to find infinity-norm of a matrix.
### Developed by:ARNMOZHI VARMAN T
### Register Number: 212223230022

import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/ArunmozhiVarmanT/Norm-of-a-matrix/assets/144870523/95cf6f28-f2f8-4b61-9ff2-8f0b22e36d50)

### 2-Norm of a Matrix
![image](https://github.com/ArunmozhiVarmanT/Norm-of-a-matrix/assets/144870523/45145d3a-e83f-4e90-b81d-53c11eb7cb54)


### Infinity Norm of a Matrix
![image](https://github.com/ArunmozhiVarmanT/Norm-of-a-matrix/assets/144870523/9d5cdb9c-40eb-48e7-be96-a231cbe0e566)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
