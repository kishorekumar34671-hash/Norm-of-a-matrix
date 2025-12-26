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
# Register No:25007664
# Developed By: KISHORE KUMAR B
```
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,1)
print(b)
```



```
# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,2)
print(round(b,2))
```



```
# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,np.inf)
print(b)
```





```
## Output:
### 1-Norm of a Matrix
<img width="834" height="780" alt="Screenshot 2025-12-26 204354" src="https://github.com/user-attachments/assets/2a2727c5-df1b-4aee-8802-6ef0a8b0a6c1" />



### 2-Norm of a Matrix
<img width="1099" height="792" alt="Screenshot 2025-12-26 204428" src="https://github.com/user-attachments/assets/1092572d-dc51-4619-a571-05d4f9fb7430" />


### Infinity Norm of a Matrix
<img width="1084" height="769" alt="Screenshot 2025-12-26 204500" src="https://github.com/user-attachments/assets/f9340dda-f095-4b10-a1bb-e4509f8d33e3" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
