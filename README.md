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

# Coding:
Import Required Libraries:
````
import matplotlib.pyplot as plt
import numpy as np
````
Ploting the graph:
````
x=np.arange(20,50)
y=np.arange(50,80)
a=np.arange(80,110)
b=np.arange(110,140)

plt.scatter(x,y,c='b')
plt.xlabel('X-Axis')
plt.ylabel('Y-Axis')
plt.title('Graph in 2D')
plt.show()

plt.plot(x,y,'b*',linestyle='dashed',linewidth='1',markersize=10)
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('2D Diagram')
plt.show()

plt.subplot(3,2,1)
plt.plot(x,y,'r.')
plt.subplot(3,2,2)
plt.plot(x,y,'b*')
plt.subplot(3,2,3)
plt.plot(x,y,'yo')
plt.subplot(3,2,4)
plt.plot(x,y,'g*')
plt.subplot(3,2,5)
plt.plot(x,y,'r.--')
plt.subplot(3,2,6)
plt.plot(x,y,'g*')

x=np.arange(1,10)
y=x*x
plt.plot(x,y,'ro')
plt.xlabel('X-Axis')
plt.ylabel('Y-Axis')
plt.title('Graph')
plt.show()

x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title('Sine Wave')
plt.plot(x,y)
plt.show()

x=np.arange(0,6*np.pi,0.1)
y_sin=np.sin(x)
y_cos=np.cos(x)

plt.subplot(2,1,1)
plt.plot(x,y_sin,'y-')
plt.title('Sine Wave')
plt.show()



plt.subplot(2,1,2)
plt.plot(x,y_cos,'b-')
plt.title('Cos Wave')
plt.show()

x=[2,4,6]
y=[3,5,7]
x2=[12,14,16]
y2=[13,15,17]
plt.bar(x,y,color='b')
plt.bar(x2,y2,color='y')
plt.title("Bar Graph")
plt.show()

a=np.array([34,65,79,90,82,10,94,39,34,92,72,49])
plt.hist(a)
plt.title("Histogram")
plt.show()

a=[np.random.normal(0, std ,100) for std in range(1,4)]
plt.boxplot(a,vert=True,patch_artist=True)
plt.show()

plt.boxplot(a,vert=False,patch_artist=False)
plt.show()

labels='RCB','CSK','MI','SRH'
sizes=[250,250, 250, 250]
colors=['red','yellow','blue','orange']
explode=(0.4,0,0,0)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%.1f')
plt.axis('equal')
plt.show()

````
# Output:

<img width="564" height="455" alt="image" src="https://github.com/user-attachments/assets/8c1a6ac7-7718-4036-8cd4-cb18c8650cb6" />

<img width="564" height="455" alt="image" src="https://github.com/user-attachments/assets/554d552b-533f-4947-b06d-98a5ce880b04" />


<img width="548" height="417" alt="image" src="https://github.com/user-attachments/assets/95d01e87-5cb0-46b3-96bb-a685b217cb10" />

<img width="562" height="455" alt="image" src="https://github.com/user-attachments/assets/957fb510-b0e3-4a2c-a0cc-da2e769fa22b" />

<img width="568" height="435" alt="image" src="https://github.com/user-attachments/assets/7ecf7195-9db3-4660-9be3-be824829d1b6" />

<img width="559" height="234" alt="image" src="https://github.com/user-attachments/assets/118c92e7-1fa8-47d9-b2ab-1762d693264b" />

<img width="559" height="234" alt="image" src="https://github.com/user-attachments/assets/8c89e1f9-9494-4530-8ed7-704cdeb449a8" />

<img width="543" height="435" alt="image" src="https://github.com/user-attachments/assets/88d7c11c-8dad-4d5e-9445-1a976065a3a8" />

<img width="547" height="435" alt="image" src="https://github.com/user-attachments/assets/f7c4a632-7a5d-410b-ae28-0bf185e1e5a1" />

<img width="546" height="413" alt="image" src="https://github.com/user-attachments/assets/5fcb089a-f05d-4cf6-bdcf-9c3c30b2b1cd" />

<img width="534" height="413" alt="image" src="https://github.com/user-attachments/assets/b4e0e865-2fc8-4837-bb5d-5608aa883b91" />


<img width="515" height="389" alt="image" src="https://github.com/user-attachments/assets/68cb249c-f20a-481e-857a-8a0be1766e14" />


# Result:
Thus , Data Visulization Using Matplotplot Library is Performed Successfully.

