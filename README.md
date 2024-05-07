# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:

Developed by : JANANI S

REG NO : 212223230086

```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```
### Line Plot :

```
marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()

student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
```
 ![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/06a93eaf-9ad6-4572-b3cb-bb59aebabece)
 ![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/ea60c729-3e96-46bb-a1d3-07a83e4e2827)

### Scatter Plot :
```
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()

x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()
```
![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/6e04c930-4a4b-40ec-a312-89e99ae1736f)
![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/0466f7da-0597-47e0-a634-89b467acba74)
### Pie Chart :
```
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()

feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/078d9082-1c97-4742-905c-45a6110906a3)
![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/9db767f4-993d-4b74-a102-f1f6263e9f93)

### Area Chart :
```
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
```
![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/c50e680b-ced0-4773-b5cc-53ac55a92afa)

### Bar Chart :
```
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green'] 
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```
![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/995ba8a4-7e52-4113-884c-e58ac884a0a5)

### Histogram :
 ```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```
![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/793df10d-6a53-49ef-9d39-45dbac6171b4)

### Box Plot :
```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
```
![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/ed9cf633-61cf-43f7-88ff-a7189705f4b3)

```
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/11ac6342-adb8-4b6a-a85f-0e57afcea6fa)


# Result:
Thus, all the data visualization techniques of matplotlib has been implemented.
