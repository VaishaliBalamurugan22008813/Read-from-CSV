# Read-from-CSV

## AIM:
To write a python program to read data from CSV file
## ALGORITHM:
### Step 1:
Start the python.
### Step 2:
Import pandas
### Step 3:
Mention the CSV file which is to be read
### Step 4:
Read the contents of the CSV file using df.read function
### Step 5:
End the program.
## PROGRAM:
```
Developed by: VAISHALI BALAMURUGAN
RegisterNumber: 22008813
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column", len(df.axes[0]))
print("rows", len(df.axes[1]))
```
## OUTPUT:
![CSV](https://user-images.githubusercontent.com/119390134/213993939-88163131-6879-4632-ae5f-5124d08ce5e6.png)

## RESULT:
A python program to read data from CSV files has been created successfully
