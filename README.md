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
Display the result.

## PROGRAM:
```
Developed by:DHARANYA.N
Register No: 212223230044

To write a python program for reading content from a CSV file.
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2023-12-24 100132](https://github.com/Dharanya2005/Read-from-CSV/assets/145742468/d62d8fc4-a66c-4aa3-bdd6-7c720e686b78)


## RESULT:
Thus python program for reading content from a CSV file is successful.
