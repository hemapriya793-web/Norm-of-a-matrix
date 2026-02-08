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
![WhatsApp Image 2026-02-09 at 12 45 34 AM](https://github.com/user-attachments/assets/a6bfc379-7b14-48d7-ac34-cc8229a40f3c)


### 2-Norm of a Matrix
![WhatsApp Image 2026-02-09 at 12 46 01 AM](https://github.com/user-attachments/assets/83508886-80f4-40fe-aa9a-4d4a58aa21b5)

### Infinity Norm of a Matrix
![WhatsApp Image 2026-02-09 at 12 47 52 AM](https://github.com/user-attachments/assets/2d617c94-7a72-4dc7-bd29-7f89e8d34250)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
