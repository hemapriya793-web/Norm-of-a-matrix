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
# Register No: 25018064
# Developed By: HEMA PRIYA S
# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
# 2-Norm of a Matrix

```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```

# Infinity Norm of a Matrix

```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

![H 1 MATH AI](https://github.com/user-attachments/assets/63b68cfa-f691-4c74-a9eb-e47b4dbdec57)


### 2-Norm of a Matrix

![H 2 MATH AI](https://github.com/user-attachments/assets/262296ea-5f1b-4659-8e83-501d9a5cce7a)


### Infinity Norm of a Matrix

![H 3 MATH AI](https://github.com/user-attachments/assets/f05f99f4-c50c-4208-b615-adfff0e8f000)

```
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
