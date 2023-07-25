# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
First, define the circulate function.
### Step 2:
Get the list value from the user. 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5:
Then, print the result.
### Step 6:
Thus the program ends.
## Program:
```
#Program to circulate N values.
#Developed by: Hari Prasath. P
#RegisterNumber: 23005079
def circulate():
    list = eval(input())
    n = int(input())
    result = list[n:] + list[:n]
    print("After circulating the values are:",result)
```

## Output:
![output](/Screenshot%202023-07-25%20183312.png)

## Result:
The Program has been executed successfully.
