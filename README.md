# Multiplying-two-matrix

## AIM:
To write a python program for multiplying two matrix.


## ALGORITHM:

Step 1:
Use import numpy as np

Step 2:
Enter the input

Step 3:
Use append()

Step 4:
use to multiply two matrix

Step 5:
print

## PROGRAM: 
```python 
import numpy as np
n=int(input())
l1,l2=[],[]
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
array1=np.array(l1)
array2=np.array(l2)
product=(array1*array2)
print("Product of two arrays is:",product)
```
## OUTPUT:
![OUTPUT](gh.png)

## RESULT:

Thus the above program is executed successfully...

