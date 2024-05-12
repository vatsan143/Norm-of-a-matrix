# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Get the input matrix using np.array()   
### Step 2: 
Find the 2-norm of the matrix using np.linalg.norm()
### Step 3 :
 Print the norm of the matrix in two decimal places.
## Program:
#Python

#Program to find norm of a Matrix

#Developed by: SRIVATSAN G

#RegisterNumber: 212223230216

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

# 3-Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-05-12 200651](https://github.com/vatsan143/Norm-of-a-matrix/assets/147368204/9a20e8ac-d430-4e06-8503-19152dba6ae0)


### 2-Norm of a Matrix
![Screenshot 2024-05-12 200711](https://github.com/vatsan143/Norm-of-a-matrix/assets/147368204/ea7583c1-4455-4c72-bc3b-3b1ac40d0dee)

### Infinity Norm of a Matrix
![Screenshot 2024-05-12 200727](https://github.com/vatsan143/Norm-of-a-matrix/assets/147368204/2aad7a4b-7c94-4236-b6b8-ff4c3265c350)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
