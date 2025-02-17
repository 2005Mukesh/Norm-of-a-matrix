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
# Register No:23006020
# Developed By:MUKESH R
# 1-Norm of a Matrix
import numpy as np 
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
nom="{:.2f}".format(ans)
print(nom)



# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
nom="{:.2f}".format(ans)
print(nom)



# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
nom="{:.2f}".format(ans)
print(nom)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-11-26 222310](https://github.com/2005Mukesh/Norm-of-a-matrix/assets/138849308/ebace46f-bdfc-44be-b471-c1569741c75b)

### 2-Norm of a Matrix
![Screenshot 2023-11-26 222320](https://github.com/2005Mukesh/Norm-of-a-matrix/assets/138849308/a8d2b078-9166-49e6-978c-a40398135b15)

### Infinity Norm of a Matrix
![Screenshot 2023-11-26 222330](https://github.com/2005Mukesh/Norm-of-a-matrix/assets/138849308/9317e6c0-4f5e-451c-a5aa-ee9df7be5dbf)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
