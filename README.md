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
```
# 1-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Darshini B
RegisterNumber:24008783
'''

import numpy as np
matrix=np.array(eval(input()))
ans=np.linalg.norm(matrix,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Darshini B
RegisterNumber:24008783
'''
import numpy as np
matrix=np.array(eval(input()))
ans=np.linalg.norm(matrix,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
'''
Program to find the Infinity of a matrix
Developed by: Darshini B
RegisterNumber:24008783
'''

import numpy as np
matrix=np.array(eval(input()))
ans=np.linalg.norm(matrix,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<br>
![image](https://github.com/user-attachments/assets/0ac0374b-48d5-49f3-9c80-0f944474aade)

<br>

### 2-Norm of a Matrix
<br>
![image](https://github.com/user-attachments/assets/0416c988-407d-4dd8-a376-d3a7414c1344)

<br>

### Infinity Norm of a Matrix
<br>
![image](https://github.com/user-attachments/assets/1977842b-828b-4e7e-965c-9b9c3b722e75)

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
