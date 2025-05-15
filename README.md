# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY
### NAME : A Vimala Rani
### REGISTER NUMBER : 212223040240

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
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
```
![ds1](https://github.com/user-attachments/assets/7f85e501-098f-4ac9-8299-d6aa0029bc94)


```
import matplotlib.pyplot as plt
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph!')
plt.show()
```

![ds2](https://github.com/user-attachments/assets/b9b8f088-c5c4-48ac-bf1f-40b95c13c862)

```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![ds3](https://github.com/user-attachments/assets/07610c81-4adb-4a11-9adb-e9f6ac44a1e2)

```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)

plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')

plt.show()
```
![ds4](https://github.com/user-attachments/assets/68fd8438-027c-42ca-902b-5748a37e717d)


```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![ds5](https://github.com/user-attachments/assets/2fd91de7-3032-4760-bc2f-2b1ca9bb3f14)


```
years=[2010,2011,2012,2013,2014,2015]
yeild_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yeild_apples)
```
![ds6](https://github.com/user-attachments/assets/bd27eeca-5581-415c-a541-af291d3e6a52)


```
years=range(2000,2012)
apples= [0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)');
```
![ds7](https://github.com/user-attachments/assets/04d14bc1-c22d-4116-9025-d3263920fb71)

```
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)')
plt.title("Crop Yeilds in Kanto")
plt.legend(['Apples','Oranges']);
```

![ds8](https://github.com/user-attachments/assets/5433d03d-b5d4-4746-8409-bb09e37b8ad8)

```
years=[2010,2011,2012,2013,2014,2015]
yeild_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yeild_apples)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)');
```
![ds9](https://github.com/user-attachments/assets/140a3c12-c879-4361-9a33-f00f44220f22)

```
years=range(2000,2012)
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yeild of Oranges (tons per hectare)");
```
![ds10](https://github.com/user-attachments/assets/33b11d79-8b3b-41fb-863b-b4c09e800ce0)

```
plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)')
plt.title("Crop Yeilds in Kanto")
plt.legend(['Apples','Oranges']);
```
![ds11](https://github.com/user-attachments/assets/7284b262-2176-4c73-88e8-50bd6fd66abb)

```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()
```
![ds12](https://github.com/user-attachments/assets/35014169-931f-4786-b1a6-a29bb1a7b565)

```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```

array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])

```
y
```

array([11, 12, 13, 14, 15, 16, 17, 18, 19, 20])


```
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![ds13](https://github.com/user-attachments/assets/3ee4736b-101b-4b59-bb0d-9b1f6d124a23)

```
y=x*x
y
```

array([ 0,  1,  4,  9, 16, 25, 36, 49, 64, 81])


```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
![ds14](https://github.com/user-attachments/assets/6e705797-457a-427d-87b3-8cde561d6da1)
```
np.pi
```

3.141592653589793

```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```

![ds15](https://github.com/user-attachments/assets/d18b2852-d934-498b-8dea-3b953827e17c)

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color="blue")
plt.fill_between(x,y2,color="green")
plt.plot(x,y1,color="red")
plt.plot(x,y2,color="black")
plt.legend(['y1','y2'])
plt.show()
```

![ds16](https://github.com/user-attachments/assets/1512df16-80a9-4233-9c9b-304520b1d208)

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
![ds17](https://github.com/user-attachments/assets/aa06f36a-9242-4dbc-b15c-7124bec7b9c6)


```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,11]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
![ds18](https://github.com/user-attachments/assets/40c2f2f1-0bf8-413b-8726-723029f664ad)


### histogram

```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No.of people')
plt.title('My histogram')
plt.show()
```

![ds19](https://github.com/user-attachments/assets/a3d3d133-c224-45c1-9d2d-26e106012f60)


### boxplot

```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```

![ds20](https://github.com/user-attachments/assets/8dc8775a-65fb-4205-83d9-005aa5fc3f95)

```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box plot'
```

![ds21](https://github.com/user-attachments/assets/fc03fc04-0dad-4080-b12d-02e1fab28604)

### pie chart

```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,
autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```

![ds22](https://github.com/user-attachments/assets/3fd8f6bd-97c1-4932-b58d-c14fbf62f8ce)

```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,
        startangle=90,shadow=True,explode=(0,0,0.1,0),
        radius=1.2,autopct='%1.1f%%')
plt.legend()
```

![ds23](https://github.com/user-attachments/assets/3d66c278-7703-412a-bfc9-a9d9e8cb0aa1)



# Result:
  To Perform Data Visualization using matplot python library for the given datas is successful.
 
