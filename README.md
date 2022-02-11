# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1:
Load the CSV into a DataFrame

### Step 2: 
Print the number of contents to be displayed using df.head()

### Step 3: 
The numbers of rows returned is defined in Pandas option settings 

### Step 4:  
Check your system's maximum column with the pd.options.display.max_column statement

### Step 5: 
Increase the maximum number of rows to display the entire Dataframe.

## PROGRAM:
```python 
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Column",len(df.axes[0]))
print("Row",len(df.axes[1]))
```
### OUTPUT:
![Output]()


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
