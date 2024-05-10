# Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee

## AIM:
To write a program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.

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
Program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.
Developed by: 
RegisterNumber:
import pandas as pd
data=pd.read_csv("/content/Salary.csv")
data.head()
data.info()
data.isnull().sum()
from sklearn.preprocessing import LabelEncoder
le=LabelEncoder()
data["Position"]=le.fit_transform(data["Position"])
data.head()
x=data[["Position","Level"]]
x.head()
y=data["Salary"]
from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=2)
from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=2)
from sklearn import metrics
mse=metrics.mean_squared_error(y_test,y_pred) 
mse
r2=metrics.r2_score(y_test,y_pred)
r2
dt.predict([[5,6]])
*/
```

## Output:
![Screenshot 2024-05-10 205745](https://github.com/Aprajith-R/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/161153978/d9f83654-8e54-462b-b56c-f4461b4c15d9)

![Screenshot 2024-05-10 205758](https://github.com/Aprajith-R/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/161153978/a8b548e5-874e-4617-a5cd-56d87d47edc1)

![Screenshot 2024-05-10 205810](https://github.com/Aprajith-R/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/161153978/21f823d7-1b9f-4d78-9e32-f5f908ec48c8)

![Screenshot 2024-05-10 205820](https://github.com/Aprajith-R/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/161153978/f33bac17-5c47-4ad5-b8cd-2eff86d866ff)

![Screenshot 2024-05-10 205830](https://github.com/Aprajith-R/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/161153978/efb3889e-1790-4060-ae08-8f1ebd6dc278)

![Screenshot 2024-05-10 205837](https://github.com/Aprajith-R/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/161153978/431308d5-85d5-4645-8c5c-6d46b29494c7)

![Screenshot 2024-05-10 205900](https://github.com/Aprajith-R/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/161153978/7c6ea69b-9fd6-44dc-9da1-2d000306474c)



## Result:
Thus the program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee is written and verified using python programming.
