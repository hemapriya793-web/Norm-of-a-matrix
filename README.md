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

![WhatsApp Image 2026-02-09 at 12 45 34 AM](https://github.com/user-attachments/assets/0329b3fe-e0f5-4852-9af2-d1c0de59a5b4)



### 2-Norm of a Matrix

![WhatsApp Image 2026-02-09 at 12 46 01 AM](https://github.com/user-attachments/assets/0ff40642-9268-4404-9e4f-6d95e47034ce)


### Infinity Norm of a Matrix

![WhatsApp Image 2026-02-09 at 12 47 52 AM](https://github.com/user-attachments/assets/b0300ccb-4aa2-4d1c-9ed3-2006863e75c2)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
