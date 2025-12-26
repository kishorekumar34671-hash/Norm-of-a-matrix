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
# 1-Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,1)
print(b)
```




# 2-Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,2)
print(round(b,2))
```




# Infinity Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,np.inf)
print(b)
```






## Output:
### 1-Norm of a Matrix
<img width="833" height="780" alt="image" src="https://github.com/user-attachments/assets/3e14d125-50be-4dfd-af1d-f49821e89b13" />


### 2-Norm of a Matrix
<img width="1098" height="792" alt="image" src="https://github.com/user-attachments/assets/645e2c21-823c-47e2-9633-575c6177a602" />



###3-Infinity Norm of a Matrix
<img width="1083" height="768" alt="image" src="https://github.com/user-attachments/assets/0157be19-03af-4fd6-b7d0-30b1f3ac9896" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
