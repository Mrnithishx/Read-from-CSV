# Read-from-CSV

## AIM:
To write a python program to read contents from a CSV file.
## ALGORITHM:
### Step 1:
import panda module as pd.
### Step 2:
Read the csv file.
### Step 3:
print the first 10rows.
### Step 4:
print the next 5rows.
### Step 5:
print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```python
#Program to read contents from a CSV file.
#Developed by:JEECIKASRINA M
#Reg No:212223100015
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
![293562199-c1d77e9e-14fe-45d6-9be7-cf2ae1331153](https://github.com/Jeecikasrina23013947/Read-from-CSV/assets/148515300/3f1399b1-9a62-41c4-83f3-08df7556462d)

## RESULT:
The program is executed successfully.
