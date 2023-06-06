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
# 1-Norm of a Matrix
```
'''
Program to find 1-norm of a matrix.
Developed by: JEEVITHA S
RegisterNumber:212222100016 
'''
array=([[-1, 3],[3, -4],[1, 7]])
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: JEEVITHA S
RegisterNumber: 212222100016
'''
import numpy as np

# Type your code here
array=([[1,2],[3,4]])
mat = np.array(eval(input()))
ans= np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
# Infinity Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: JEEVITHA S
RegisterNumber: 212222100016
'''
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/Jeevithha/Norm-of-a-matrix/assets/123623197/abaa3a97-d5d9-4f7e-84a0-e32d9b160046)

### 2-Norm of a Matrix

![image](https://github.com/Jeevithha/Norm-of-a-matrix/assets/123623197/f02bd6dd-308b-48e7-8585-b7209199aedc)

### Infinity Norm of a Matrix

![image](https://github.com/Jeevithha/Norm-of-a-matrix/assets/123623197/2823d1a9-36a1-4c81-82a4-aa8da6e5e88d)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
