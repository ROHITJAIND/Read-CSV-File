# Read from CSV

## AIM:
To write a python program to read contents from a CSV file.
## ALGORITHM:
- Step 1:  
  - Import pandas module as pd. 
- Step 2:  
  - Using pd.read_csv() method read the CSV file.
- Step 3:  
  - Using df.head() print the first 10 rows of the CSV file.
- Step 4:  
  - Using df.tail() print the last 5 of the CSV file.
- Step 5:  
  - Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```Python
#Program to read contents from a CSV file.
#Developed by: ROHIT JAIN D
#RegisterNumber: 212222230120

```  


```Python
import pandas as pd
df = pd.read_csv("data.csv")
print(df.head(10))
print(df.tail())
print("No.of Rows:",len(df.axes[0]))
print("No.of Columns:",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2023-06-04 125922](https://github.com/ROHITJAIND/Read-CSV-File/assets/118707073/e6ecec2c-dab4-4e4b-899b-48834d5ec733)

## RESULT:
Hence the python programe to read the contents from a csv file is executed successfully!
