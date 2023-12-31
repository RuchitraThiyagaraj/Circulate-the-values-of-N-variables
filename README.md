# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
define a function named circulate
### Step 2:
get a list input from the user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
print the sliced list
### Step 6: 
call the function circulate
## Program:
~~~
#Program to circulate N values.
#Developed by: RUCHITRA THIYAGARAJ
#RegisterNumber:23000100
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
circulate()
~~~
## Output:
![image](https://github.com/RuchitraThiyagaraj/Circulate-the-values-of-N-variables/assets/154776996/c12b2992-1193-4707-a59a-29c7f67a9088)


## Result:
Thus circulating the n values are successfully executed
