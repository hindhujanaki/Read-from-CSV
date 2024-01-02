# Read-from-CSV

## AIM:

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
Use len() method to get the number of rows and columns.
## PROGRAM:
```
'''
#Program to read contents from a csv file
#Developed by: G.Hindhu
#Register Number:23014493
'''
import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2024-01-02 202047](https://github.com/hindhujanaki/Read-from-CSV/assets/148514666/7151e8b9-f02f-452f-b5eb-db8a9fd96e66)
## RESULT:
Thus the program is written to copy the contents from one file to another file
