# Read-from-CSV

## AIM:
To write a python program to read contents from the csv file

## ALGORITHM:
### Step 1:
import panda as pd
### Step 2:
Read the csv file using read_csv method.
### Step 3:
use head and tail method to get the required contents from the file.
### Step 4:
use len() method to get the number of rows and columns 
### Step 5:

print the output

## PROGRAM:

import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("No of rows",len(df.axes[0]))
print("No of columns",len(df.axes[1]))

## OUTPUT:

![GitHub Logo](/image.png)

## RESULT:
Thus the given python program to solve the contents of the csv file