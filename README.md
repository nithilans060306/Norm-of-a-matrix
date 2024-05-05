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
# Register No: 212223240108
# Developed By: Nithilan S
# 1-Norm of a Matrix
import numpy as np
n = np.array(eval(input()))
ans = np.linalg.norm(n,1)
print("{:.2f}".format(ans))



# 2-Norm of a Matrix
import numpy as np
n = np.array(eval(input()))
ans = np.linalg.norm(n,2)
print("{:.2f}".format(ans))



# Infinity Norm of a Matrix
import numpy as np
n = np.array(eval(input()))
ans = np.linalg.norm(n,np.inf)
print("{:.2f}".format(ans))




```
## Output:
### 1-Norm of a Matrix
![Exp7_1](image.png)

### 2-Norm of a Matrix
![Exp7_2](image-1.png)

### Infinity Norm of a Matrix
![Exp7_3](image-2.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
