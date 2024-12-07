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
# Register No:Harshadharshini.R
# Developed By:24900177
# 1-Norm of a Matrix
```
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

![Screenshot (5)](https://github.com/user-attachments/assets/c0647204-a53e-4636-b9ff-0a5b67007fd6)

### 2-Norm of a Matrix
![Screenshot (6)](https://github.com/user-attachments/assets/5aef1d85-ce54-4c62-a69e-6c28e223ed57)


### Infinity Norm of a Matrix
![Screenshot (7)](https://github.com/user-attachments/assets/ceeafbe4-abed-4dbf-8f20-9adc39757d6b)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
