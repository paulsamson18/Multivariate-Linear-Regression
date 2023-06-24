# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>Import panda module as pd

### Step2
<br>mport linear model from sklearn

### Step3
<br>Read the file cars.csv

### Step4
<br>Assign the values for x and y as required

### Step5
<br>Create the linearRegression model and predict the output

## Program:
```
Developed by: paulsamson s
Register number: 212222230104

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars.csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))






```
## Output:
![image](https://github.com/paulsamson18/Multivariate-Linear-Regression/assets/119405794/39858e80-4a1e-4e22-a0e9-a030773626d9)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
