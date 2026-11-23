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
# 1-Norm of a Matrix
```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np 
a=np.array(eval(input()))
norm1=np.linalg.norm(a,1)
norm="{:.2f}".format(norm1)
print(norm)
```
# 2-Norm of a Matrix
```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,2)
norm="{:.2f}".format(norm1)
print(norm)
```

# Infinity Norm of a Matrix
```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(norm1)
print(norm)
```

## Output:
### 1-Norm of a Matrix
<img width="1406" height="350" alt="image" src="https://github.com/user-attachments/assets/3ed0595e-3414-4a3f-b34b-1598f33cb0cf" />

### 2-Norm of a Matrix
<img width="1396" height="416" alt="image" src="https://github.com/user-attachments/assets/5fa96500-752a-419c-a51c-c9206a3c7749" />

### Infinity Norm of a Matrix
<img width="1372" height="350" alt="image" src="https://github.com/user-attachments/assets/7b27e028-099d-49fc-8b99-a6e3d7837153" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
