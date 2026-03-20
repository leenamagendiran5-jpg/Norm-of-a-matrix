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
# Register No:212225220056
# Developed By:LEENA SHREE M

# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

![WhatsApp Image 2026-03-20 at 4 13 44 PM](https://github.com/user-attachments/assets/2bb66d9a-59e6-4c58-9685-201f71e40e1c)

### 2-Norm of a Matrix

![WhatsApp Image 2026-03-20 at 4 13 57 PM](https://github.com/user-attachments/assets/0ca6dd7a-9b2e-4726-9ccc-c094912f4b50)

### Infinity Norm of a Matrix

![WhatsApp Image 2026-03-20 at 4 13 33 PM](https://github.com/user-attachments/assets/0f31c706-0189-49a4-b7c5-ed03dcdf3965)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
