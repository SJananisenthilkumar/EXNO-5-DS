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
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label='line1')
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label='line2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/013958ee-058f-42d8-b1e7-02b7590f4a32)

```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/5708d34c-c853-4c80-90a9-b6ab0ecf7b68)

```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/d09c0a46-d3fa-423f-8013-e3d6af1fe738)

```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/df250a26-66d6-484a-bad5-54a83a56aea0)

```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples','Oranges']);
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/9e277746-6e17-4fac-854a-8d412ce3d9ac)

```
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yield of Oranges (tons per hectare)");
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/a5b5d84b-47ad-406c-885f-e817dd7b841d)

```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/4f0c3ef0-6dd2-430e-a6dc-c2f2b7cba434)

```
y
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/8bd0928a-0105-4469-91f0-d0b41b1b82ea)

```
plt.scatter(x,y,c='r')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/694257b8-07fc-44b6-9b95-4040e8a05c2c)

```
y=x*x
y
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/89c17737-98cb-41e6-bee6-d8f2c639bc8a)

```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/caa6c407-a4e0-452b-9c16-bbf3d6341431)

```
np.pi
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/6e4aa6f0-bf96-4a59-b1af-f4abd6ce1389)

```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/f046c046-0b86-4516-b731-5211016586db)

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/c65508c1-c4d2-4843-ba40-67b60c2bac71)

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')

plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/c52e9a92-9e4d-41fd-a79b-7bad9fad12ac)

```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/c52642c6-bf25-4d33-9a14-3e23be7552e7)

```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/70ccf496-0d27-41ca-8e71-396522472c38)

```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/7a7f3a62-7478-4aa0-beca-927fbef19619)

```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/a455b89a-06b2-4a5a-9999-29dad6a645eb)

```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/db72af91-2863-42ce-b66f-7ccf1eaaa586)

```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/f5caa903-4906-4cdc-94bc-e519f824981a)

```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```

![image](https://github.com/SJananisenthilkumar/EXNO-5-DS/assets/144871139/aa11867c-a125-4444-ae30-dc543bfe8629)

# Result:

Thus, all the data visualization techniques of matplotlib has been implemented.
