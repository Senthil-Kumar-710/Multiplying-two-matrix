# Multiplying-two-matrix

## AIM:

To write a python program for multiplying two matrix.

## ALGORITHM:

### Step 1:
Import Numpy as np.

### Step 2:
Get input from the user.



### Step 3:

Create empty lists l1 and l2.
### Step 4:

Use for loop to append the values into the list created.
### Step 5:
Print the product of two arrays.

## PROGRAM: 
```
import numpy as np
n=int(input())
l1,l2=[],[]
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
A=np.zeros((n))
l3=[]
for i in range(n):
    l3.append(l1[i]*l2[i])
A=np.array(l3)
print("Product of two arrays is:",A)
```
## OUTPUT:

![Capture](https://user-images.githubusercontent.com/93860256/153714811-106fa9c1-d774-477a-846f-fff327a93542.PNG)


## RESULT:

Thus, the program is written to multiply two matrix.