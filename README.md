# Read-from-CSV
## AIM:To read a csv file and access the data
## ALGORITHM:
### Step 1:
Import Pandas module

### Step 2:
Import linear_module from sklearn

### Step 3:
Declare data frame df to read the csv file

 ### Step 4:
Declare variable X equal to df with two arguments Weight and Volume

### Step 5:
Declare variable y equal to df with an argument CO2

### Step 6:
Declare a variable regr equal to linear_model.LinearRegression()

### Step 7:
declare regr.fit(X,y)

### Step 8:
Print regr.coeff_

### Step 9:
Print regr.intercept_

### Step 10:
Declare variable predictedCO2 equal to regr.predict with two arguments 33300, 1300

### Step 11:
Print variable predictedCO2

## PROGRAM:
~~~
#Developed by : v.charan sai
#Reference number:- 212221240061
import pandas as pd
df=pd.read_csv('pd.csv')
print(df.head())
print(df.tail())
print("column",len(df.axes[0]))
print("rows",len(df.axes[1]))

~~~
## OUTPUT:
![output](https://github.com/charansai0/Read-from-CSV/blob/main/1111.png?raw=true)

## RESULT:
Therefore the program is successfully executed to read csv file and access the data in it.