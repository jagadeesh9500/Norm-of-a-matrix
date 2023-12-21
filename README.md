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
# Register No:23013534
# Developed By:JAGADEESH P
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))



# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))




# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))





```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/jagadeesh9500/Norm-of-a-matrix/assets/149087921/533293fe-46ae-4994-8f09-5aedb9f522dd)


### 2-Norm of a Matrix
![image](https://github.com/jagadeesh9500/Norm-of-a-matrix/assets/149087921/24b5833d-8b0f-4dda-915d-5c2cd9839095)


### Infinity Norm of a Matrix
![image](https://github.com/jagadeesh9500/Norm-of-a-matrix/assets/149087921/1a581673-1775-4d8b-9fc5-76e87f61dbc2)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
