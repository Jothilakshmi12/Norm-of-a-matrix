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
# Register No: 212223110017
# Developed By: Jothilakshmi
# 1-Norm of a Matrix
'''
program to find 1-norm
Developed by: Jothilakshmi
RegisterNumber: 212223110017
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))
'''

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Jothilakshmi
RegisterNumber: 212223110017
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))
'''


# Infinity Norm of a Matrix
'''
program to find the infinity of a matrix
Developed by : Jothilakshmi
RegisterNumber: 212223110017
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
'''

```
## Output:
### 1-Norm of a Matrix
![normoutput1](https://github.com/Jothilakshmi12/Norm-of-a-matrix/assets/138849182/c7a06c8e-cc8d-45ee-8fa4-0d67601d41e8)


### 2-Norm of a Matrix
![normoutput2](https://github.com/Jothilakshmi12/Norm-of-a-matrix/assets/138849182/1c1970f9-eed4-4786-89ff-96ce446f882f)


### Infinity Norm of a Matrix
![normoutput3](https://github.com/Jothilakshmi12/Norm-of-a-matrix/assets/138849182/945672db-dd07-4d02-9f1f-59734cd4c69d)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
