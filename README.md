NORM-OF-A-MATRIX

Aim:
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

Equipment’s required:
Hardware – PCs
Anaconda – Python 3.7 Installation / Moodle-Code Runner
 
 Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
Program:
# Register No: 22009081
# Developed By:anbuselvam
###Program
```
# 1-Norm of a Matrix

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

### output:
 1 norm of matrix

 ![output](/1%20norm%20of%20matrix.png)

 2 norm of matrix

 ![output](/2norm%20of%20matrix.png)

infinity norm of matrix
![output](/Screenshot%20(79).png)

RESULT

Thus the program for 1-norm,2-norm and infinity norm of matrix are written and verified
