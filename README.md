# Read-from-CSV

## AIM:
To write a python program to read contents from a CSV file.
## ALGORITHM:
### Step 1:
import panda module as pd
### Step 2:
Read the csv file
### Step 3:
print the first 10rows
### Step 4:
print the next 5rows
### Step 5:
print the toal no.of rows and columns with argument 0 for row and argument 1 for column.
## PROGRAM:
```python
#Program to read contents from a CSV file.
#Developed by:NITHISH MD
#Reg No: 23009587
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[1])
print("no of rows",len(df.axes[0]))
print("no. of columns",len(df.axes[1]))
```
## OUTPUT:
![293562199-c1d77e9e-14fe-45d6-9be7-cf2ae1331153](https://github.com/Mrnithishx/Read-from-CSV/assets/148201573/a2a1ee50-388e-4d8e-8443-766007f6251a)

## RESULT:
