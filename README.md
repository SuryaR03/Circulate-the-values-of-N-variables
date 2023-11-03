430I # Circulate-the-values-of-N-variables  
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
start the program
### Step 2: 
get the input from the user  using eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
using concatenation display the entire rotated list 
### Step 6: 
stop the program
## Program
#Program to circulate N values.
#Developed by: SURYA R
#RegisterNumber:23013019
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
    
## Output

![image](https://github.com/SuryaR03/Circulate-the-values-of-N-variables/assets/147140237/0f267b7e-32ee-4db8-b950-429279a119b6)


## Result:
