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
# Register No:KEERTHIKA M P
# Developed By:212223240071
# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```


# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-05-06 202709](https://github.com/Keerthika23013559/Norm-of-a-matrix/assets/162658262/5696e9bd-cff4-496f-a6f3-4f67bb896abe)


### 2-Norm of a Matrix
![Screenshot 2024-05-06 202724](https://github.com/Keerthika23013559/Norm-of-a-matrix/assets/162658262/a48b7fce-6cfb-4426-907e-dbc03864f121)


### Infinity Norm of a Matrix
![Screenshot 2024-05-06 202736](https://github.com/Keerthika23013559/Norm-of-a-matrix/assets/162658262/56ac0dea-1052-4a2c-a9e7-5e2a076c81b2)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
