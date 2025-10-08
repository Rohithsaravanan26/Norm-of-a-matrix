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
# Register No:25008317
# Developed By:Rohith S
```
```
# 1-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)
```
```
# 2-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")
```
```
# Infinity Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)
```


## Output:
### 1-Norm of a Matrix
<img width="878" height="711" alt="Screenshot 2025-10-08 141711" src="https://github.com/user-attachments/assets/548c5675-f403-431e-8db5-35f8f35d7283" />

### 2-Norm of a Matrix
<img width="859" height="746" alt="Screenshot 2025-10-08 141725" src="https://github.com/user-attachments/assets/63022f5d-9198-44c2-81f0-d3829d5a5f6d" />

### Infinity Norm of a Matrix
<img width="852" height="729" alt="image" src="https://github.com/user-attachments/assets/644f4c1f-e1ed-4b65-a7be-efff62a54be8" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
