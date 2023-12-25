# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.
## ALGORITHM:
### Step 1:Import pandas as pd.
### Step 2:Read the CSV file using read_csv method.
### Step 3:Use head and tail method to get the required contents from the file.
### Step 4:Use len() method to get the number of rows and columns
### Step 5:Print the output.

## PROGRAM:
```
'''
Developed by:MOHAMED FAROOK S
Register No: 23014058
'''
To write a python program for reading content from a CSV file.
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:", len (df.axes[0]))
print("Number of columns:",len(df.axes[1]))

```
## OUTPUT:
![image](https://github.com/MOHAMEDFAROOK2005/Read-from-CSV/assets/150319482/3235698a-d771-4e37-b68b-67398416001a)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
