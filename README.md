# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
## Step 1:
Import pandas module as pd.
## Step 2:
Using pd.read_csv() method read the CSV file.
## Step 3:
Using df.head() print the first 10 rows of the CSV file.
## Step 4:
Using df.tail() print the last 5 of the CSV file.
## Step 5:
Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.
### Step 5:
Display the result


## PROGRAM:
```
#Program to read contents from a CSV file.
#Developed by: DIVYA K
#RegisterNumber: 212222230035


import pandas as pd
df = pd.read_csv("data.csv")
print(df.head(10))
print(df.tail())
print("No.of Rows:",len(df.axes[0]))
print("No.of Columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/divyakumars/Read-from-CSV/assets/119393621/92fc22d0-3bdc-4a13-98fc-c2999f918550)




## RESULT:
Thus python program for reading content from a CSV file is successful.
