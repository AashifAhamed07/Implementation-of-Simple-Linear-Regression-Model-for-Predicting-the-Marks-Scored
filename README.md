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
```
/*
Program to implement the simple linear regression model for predicting the marks scored.
Developed by: Aashif Ahamed S
RegisterNumber:  212225040004
*/
import numpy as np
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression
X=np.array([1,2,3,4,5]).reshape(-1,1)
Y = np.array([35,50,65,70,85])
model = LinearRegression()
model.fit(X,Y)
x_input = float(input("Enter hour studied: "))
predicted_marks = model.predict([[x_input]])
print("Predicted Marks:",predicted_marks[0])
y_pred = model.predict(X)
plt.scatter(X,Y,label="Actual Data")
plt.plot(X,y_pred,label="Regression line")
plt.xlabel("Hours Studied")
plt.ylabel("Marks Scored")
plt.title("Simple Linear Regression(Using sklearn)")
plt.legend()
plt.show()
```

## Output:
![simple linear regression model for predicting the marks scored](sam.png)
<img width="453" height="133" alt="image" src="https://github.com/user-attachments/assets/7fd4be33-6805-462b-8890-a75a9c80ada7" />
<img width="736" height="577" alt="image" src="https://github.com/user-attachments/assets/cfbb3f8e-121b-4430-b1c7-290896c49029" />


## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
