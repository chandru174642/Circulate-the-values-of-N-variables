# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a user defined function
### Step 2: 
Get the variables from user to enter inside the list
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5:
After rotating the variables , store the rotated variables in a seperate list
### Step 6: 
At last , print the list of rotated variables
## Program:
#Program to circulate N values.
#Developed by: CHANDRU P
#RegisterNumber:23007250
```
def circulate():
    l1=eval(input())
    a=int(input())
    l2=[]
    for i in range(a,len(l1)):
        l2.append(l1[i])
    for i in range(a):
        l2.append(l1[i])
    print("After circulating the values are:",l2)
```
## Output:

![circulates](https://github.com/chandru174642/Circulate-the-values-of-N-variables/assets/139841798/9e34fcc4-3ea6-4a41-b638-b201fa1da374)

## Result:
output verified sucessfully

