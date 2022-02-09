# Multiplying-two-matrix

## AIM:
To write a python program for multiplying two matrix.
## EQUIPEMENT'S REQUIRED:
PC Anaconda - python 3.7

## ALGORITHM:

### Step 1:
Use import numpy as np
### Step 2:
Enter the input
### Step 3:
Use append()
### Step 4:
use to multiply two matrix
### Step 5:
print.
```
## PROGRAM: 
## DEVELOPED BY : J.DEEPIKA
## REGISTER NUMBER : 212221230016
import numpy as np
l1, l2 =[],[]
n= int(input())
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
value1= np.array(l1)
value2= np.array(l2)
result = value1*value2
print("Product of two arrays is:",result)
```

## OUTPUT:
![output](.//a1.PNG)

## RESULT:
Thus the program is written to multiply two matrix.

