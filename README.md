# Read-from-CSV

## AIM:
To write a python program for reading content from a csv file

## ALGORITHM:
### Step 1:
Import pandas as pd.

### Step 2:
Read the CSV file using read csv method.

### Step 3:
Use head and tail method to get the required contents from the file.

### Step 4:
Use len() method to get the number of rows and columns.

### Step 5:
Display the result.

## PROGRAM:
```
##Developed by: Beatrice Thomas
##RegisterNumber: 23005036
To write a python program for reading content from a CSV file.
import pandas as pd
df pd.read_csv('data.csv')
print(df.head(10)) print(df.tail())
print("Number of rows:", len(df.axes[e]))
print("Number of columns:", len(df.axes[1]))
```
## OUTPUT:

![Alt text](<Screenshot 2023-12-30 100839.png>)

## RESULT:
Thus the python program for reading the csv file is successful.