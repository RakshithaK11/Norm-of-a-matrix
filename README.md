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
~~~
# Register No:RAKSHITHA K
# Developed By:23003887
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))
~~~
## 2-Norm of a Matrix
~~~
'''
Program to find 2-norm of a matrix.
Developed by:   RAKSHITHA K 
RegisterNumber: 23003887
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))
~~~
## Infinity Norm of a Matrix
~~~
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
~~~
## Output:


### 1-Norm of a Matrix
![image](https://github.com/RakshithaK11/Norm-of-a-matrix/assets/139336455/b1fcf8c6-35ef-4bf6-a4b7-f606e30fe318)


### 2-Norm of a Matrix
![image](https://github.com/RakshithaK11/Norm-of-a-matrix/assets/139336455/ca664f89-3d9e-4600-aa09-104ff5cbd3af)


### Infinity Norm of a Matrix
![image](https://github.com/RakshithaK11/Norm-of-a-matrix/assets/139336455/cc0ea21f-e1fd-4824-b9a8-46ab7312642c)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
