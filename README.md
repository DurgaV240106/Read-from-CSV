# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
Print the output.
## PROGRAM:
```
#To write a python program for reading content from a CSV file.
##Developed by:  DURGA V
##Register Number: 23013532

import pandas as pd
df = pd.read_csv('drg.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
<img width="426" alt="Screenshot 2024-01-03 013516" src="https://github.com/DurgaV240106/Read-from-CSV/assets/144870878/5235747f-7f8b-4aaf-874a-92deaa21fa69">

## RESULT:
Thus a python program is written to read the contents of a CSV file.
