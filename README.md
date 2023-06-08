# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
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
![image](https://github.com/divyakumars/Read-from-CSV/assets/119393621/a825ab42-6ec6-40be-8a05-3602af6a0f49)



## RESULT:
Thus python program for reading content from a CSV file is successful.
