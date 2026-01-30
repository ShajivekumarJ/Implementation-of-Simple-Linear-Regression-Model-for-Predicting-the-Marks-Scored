# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. 
2. 
3. 
4. 

## Program:
/*
Program to implement the simple linear regression model for predicting the marks scored.
Developed by: SHAJIVE KUMAR J
RegisterNumber:  25018897
*/
~~~
import numpy as np
from sklearn.linear_model import LinearRegression
import matplotlib.pyplot as plt

x=np.array([1,3,2,6,9,7,8,2]).reshape(-1,1)
y=np.array([50,73,66,88,97,75,83,60])

model=LinearRegression()
model.fit(x,y)
y_=model.predict(x)

print("Slope:",model.coef_[0])
print("Intercept:",model.intercept_)

plt.scatter(x,y,color='grey',label="Actual Marks")
plt.plot(x,y_,color='blue',label="Predicted Marks")
plt.xlabel("Total Number of Materials used")
plt.ylabel("Marks Obtained")
plt.legend()
plt.show()
~~~

## Output:
<img width="686" height="767" alt="Screenshot 2026-01-27 214644" src="https://github.com/user-attachments/assets/1eee98fc-b56b-4095-9987-e7a773bea08b" />



## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
