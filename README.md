# Inverse-of-matrix

## AIM:

## ALGORITHM:
### Step 1:
Import Numpy module as np.
### Step 2:
Create empty lists.
### Step 3:
Get input from the user for number of rows and columns.
### Step 4:
Use nested lists to append list.
### Step 5:
Print the inverse of the array using np.linalg.inv


## PROGRAM:
```
#To find the inverse of a matrix
#Developed By: GAUTHAM M G
#Register Number: 212221230027
import numpy
rows=int(input())
columns=int(input())
l1=[]
for i in range(rows):
    temp=[]
    for j in range(columns):
        t=int(input())
        temp+=[t]
    l1+=[temp]
print(l1)
print(numpy.linalg.inv(l1))
```

## OUTPUT:
![image](https://user-images.githubusercontent.com/94810884/153756163-bbc2fe29-13c9-4074-8cd3-b8362da7b62a.png)


## RESULT:
Thus a program is written to find the inverse of the matrix.
