# Read-from-CSV

## AIM:
To develop a program to read from a csv file

## EQUIPMENTS REQUIRED
Hradware-PC
Software-Python 3.7
## ALGORITHM:
### Step 1:
Import the pandas library
### Step 2:
Read the csv file usinf read_csv method()
### Step 3:
Use file.head() method to read from beginning
### Step 4:
Use file.tail() method to read from end
### Step 5:
End the program
## PROGRAM:
``` python
'''
Program to read from csv file
Developed By:A.J.PRANAV
Reference Number:22008772
'''
import pandas as pd
f=pd.read_csv('/content/cars (1).csv')
print(f.head(10))
print(f.tail())
print(len(f.axes[0]))
print(len(f.axes[1]))
```
## OUTPUT:
![output](./CSV.png)
## RESULT:
Hence the program to read from a csv file is executed.