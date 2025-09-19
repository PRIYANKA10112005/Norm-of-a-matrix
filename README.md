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
# 1-Norm of a Matrix
'''
Program to find the 1-Norm of a matrix and display the results in two decimal places.
Developed by : PRIYANKA P 
Register number: 21222230212
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: Priyanka P
RegisterNumber: 212224230212
'''
import numpy as np
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)



# Infinity Norm of a Matrix

'''
Program to find Infinity norm of a matrix.
Developed by: PRIYANKA P
RegisterNumber: 212224230212
'''
import numpy as np
mat=np.array(eval(input()))

norm=np.linalg.norm(mat,ord=np.inf)
print("{:.2f}".format(norm))




```
## Output:
### 1-Norm of a Matrix
<img width="1312" height="975" alt="Screenshot 2025-09-19 104050" src="https://github.com/user-attachments/assets/8a0ac82c-b82e-485b-9c23-a39c432105e9" />

<br>
<br>
<br>

### 2-Norm of a Matrix

<br><img width="1238" height="949" alt="Screenshot 2025-09-19 104123" src="https://github.com/user-attachments/assets/ff12a64a-0507-4f12-9cc3-acb75d1a40e5" />

<br>
<br>

### Infinity Norm of a Matrix
<img width="1277" height="960" alt="Screenshot 2025-09-19 104137" src="https://github.com/user-attachments/assets/97cc5724-2c97-4df6-84dc-b582532d549f" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
