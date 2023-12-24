# Read-from-CSV

## AIM:

## ALGORITHM:
### step1:
Create a spreadsheet with any details in it with extension .csv
### Step 2:
Open google colab and mount the drive for using the created file in the colab
### Step 3:
import pandas package as pdf for reading the csv file using pd.read_csv(filename)
### Step 4:
use the function called head() and tail() for printing the top and bottom of the file and then axes[]
used for inding the number of rows and columns
### Step 5:
End of program

## PROGRAM:
```
import pandas as pd
f=pd.read_csv('cars (1).csv')
print(f.head(10))
print(f.tail())
print("rows",len(f.axes[0]))
print("columns",len(f.axes[1])
```
## OUTPUT:
<img width="508" alt="image" src="https://github.com/Vigneshv-23/Read-from-CSV/assets/110780412/c74ceb55-e047-4fd6-b940-17fccf073400">


## RESULT:
Thus python program for reading content from a CSV file is successful.
