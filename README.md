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
```
Register Number : 212224230184
Completed by : Nethra.K
```

```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
```

### Line Plot :
```
marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student Name')
plt.show()

student=['A','B','C','D']
attendance=[90,85,73,88]
plt.plot(attendance,student)
plt.xlabel('Attendance')
plt.ylabel('Student Name')
plt.show()

```

<img width="575" height="432" alt="image" src="https://github.com/user-attachments/assets/ff9332cb-2d3c-4fc7-b2bf-868e9e1b7374" />

<img width="556" height="420" alt="image" src="https://github.com/user-attachments/assets/75e582b6-ea15-4221-bb42-7138a060dcbc" />

### Scatter Plot :
```
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',marker='*',color='purple',s=50)
plt.show()

x=np.arange(0,15)
y=np.arange(0,15)


x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Scatter plot')
plt.show()
```

<img width="651" height="841" alt="image" src="https://github.com/user-attachments/assets/c4ee533c-3ad3-49d3-87b9-23a6dad510d2" />

### Pie Chart :
```
act =['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','b','g','y']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()

feedback=['Good','Excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['g','b','r','y']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
<img width="594" height="799" alt="image" src="https://github.com/user-attachments/assets/e408dadb-1dc7-4007-94ae-44eebe29faf5" />

### Area Chart :
```
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='b')
plt.fill_between(x,y2,color='g')
plt.plot(x,y1,color='r')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```

<img width="610" height="411" alt="image" src="https://github.com/user-attachments/assets/65268be6-f3ed-4122-a803-910ac0a52611" />

### Bar Chart :
```
height=[10,24,36,40,5]
names=['one','two','three','foue','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c2)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()

```

<img width="574" height="441" alt="image" src="https://github.com/user-attachments/assets/8086ed9b-5b64-4487-b68a-2e356524a745" />

### Histogram Plot:
```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()
```

<img width="534" height="413" alt="download" src="https://github.com/user-attachments/assets/1fdb3e48-06b5-43f4-91e7-c12b0ccd8a65" />

### Box Plot :
```
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```

<img width="619" height="409" alt="image" src="https://github.com/user-attachments/assets/9ebb0815-385c-4802-a0de-129520c0c0b3" />

```
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```

<img width="593" height="459" alt="image" src="https://github.com/user-attachments/assets/e4af3746-6e17-47ca-abeb-085853c75057" />


# Result:
 Thus, all the data visualization techniques of matplotlib has been implemented.
