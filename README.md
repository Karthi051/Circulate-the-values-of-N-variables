# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
start the program
### Step 2: 
Get input from user using eval(input)
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Using the concatination operation display the entire rotated list
### Step 6: 
stop the program
## Program:
```
#Program to circulate N values.
#Developed by: karthi keyan
#RegisterNumber:23013936
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)


```

## Output:
![Alt text](<Screenshot 2023-11-29 222821.png>)
## Result:
This program is completed successfully..
