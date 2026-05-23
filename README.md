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
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
```

<img width="710" height="540" alt="Screenshot 2026-05-23 170503" src="https://github.com/user-attachments/assets/75715b04-7776-46b5-b5c0-3d1590e43217" />

```
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph')
plt.show()
```

<img width="768" height="557" alt="Screenshot 2026-05-23 170559" src="https://github.com/user-attachments/assets/29a2bb75-aaef-4f29-afb2-6b76f4770143" />

```
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph')
plt.legend()
plt.show()
```

<img width="798" height="540" alt="Screenshot 2026-05-23 170724" src="https://github.com/user-attachments/assets/2d46ad88-4f9f-42c0-a1b0-23d3c461e3e9" />

```
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue') # Added closing quote and a color 'blue'
plt.ylim(1,8)
plt.xlim(1,8)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations')
plt.show()
```

<img width="762" height="565" alt="Screenshot 2026-05-23 170836" src="https://github.com/user-attachments/assets/1c4ed6ab-0d54-44e4-b9f6-29ec243a87d4" />

```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```

<img width="794" height="555" alt="Screenshot 2026-05-23 170946" src="https://github.com/user-attachments/assets/1865a28d-422d-4048-8e2f-159b37255648" />

```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9375,0.895] 
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.895] 
plt.plot(years , apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)');
```

<img width="756" height="536" alt="Screenshot 2026-05-23 171059" src="https://github.com/user-attachments/assets/3a2c8caf-e91a-446b-8cce-2cb1f8f21009" />

```
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)')
plt.title("Crop yield in Kanto")
plt.legend(['Apples','Oranges'])
```

<img width="839" height="545" alt="Screenshot 2026-05-23 171212" src="https://github.com/user-attachments/assets/f7570085-490b-4351-bc9b-c80c8710dde3" />

```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="red")
plt.show()
```

<img width="818" height="512" alt="Screenshot 2026-05-23 171324" src="https://github.com/user-attachments/assets/74738503-34e2-4684-a825-9db20abcc2eb" />

```
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```

<img width="781" height="565" alt="Screenshot 2026-05-23 171430" src="https://github.com/user-attachments/assets/b786c49e-2874-4921-9a9b-a35f865ef8ef" />

```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('x axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```

<img width="728" height="567" alt="Screenshot 2026-05-23 171518" src="https://github.com/user-attachments/assets/c54011a0-da52-4e9d-a506-2b55bdea20ea" />

```
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
```

<img width="728" height="537" alt="Screenshot 2026-05-23 171636" src="https://github.com/user-attachments/assets/641b9eaa-4985-4311-83ee-0163f9b7d11d" />

```
import numpy as np

print(np.pi)
```

<img width="225" height="67" alt="Screenshot 2026-05-23 171738" src="https://github.com/user-attachments/assets/263fc5b1-1fd9-404a-97c3-6a4d4996ac8e" />

```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```

<img width="733" height="547" alt="Screenshot 2026-05-23 171828" src="https://github.com/user-attachments/assets/8db6010a-91ea-46d9-9fa8-8135d7fa78fa" />

```
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

<img width="800" height="522" alt="Screenshot 2026-05-23 171955" src="https://github.com/user-attachments/assets/57631d67-c901-4ff2-99c0-02b8444a3899" />

```
plt.stackplot(x,y1,y2,y3,labels=['Line 1','Line 2','Line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```

<img width="835" height="537" alt="Screenshot 2026-05-23 172133" src="https://github.com/user-attachments/assets/bd19ad0b-86e5-452c-977e-1be198d4633e" />

```
import numpy as np
import matplotlib.pyplot as plt
from scipy.interpolate import make_interp_spline
x=np.array([1,2,3,4,5,6,7,8,9,10])
y=np.array([2,4,5,7,8,8,9,10,11,12])
spl=make_interp_spline(x,y)
x_smooth=np.linspace(x.min(),x.max(),100)
y_smooth=spl(x_smooth)
plt.plot(x,y,'o',label='data')
plt.plot(x_smooth,y_smooth,'-',label='Spline')
plt.legend()
plt.show()
```

<img width="721" height="535" alt="Screenshot 2026-05-23 172210" src="https://github.com/user-attachments/assets/e1d6eac6-5264-4dd0-83fb-f6069897dae7" />

```
import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.bar(names,values,color="green")
plt.show()
```

<img width="728" height="504" alt="Screenshot 2026-05-23 172251" src="https://github.com/user-attachments/assets/0286b371-62d5-4ef9-9ded-e2eece937a47" />

```
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.barh(names,values,color="yellowgreen")
plt.show()
```

<img width="716" height="501" alt="Screenshot 2026-05-23 172328" src="https://github.com/user-attachments/assets/8ddc0570-6961-4d49-aec7-89eff1f6f5b0" />

```
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My Bar Chart!')
plt.show()
```

<img width="811" height="550" alt="Screenshot 2026-05-23 172401" src="https://github.com/user-attachments/assets/fc457c12-71c9-48e3-9683-dea5bde0bfc3" />

```
x=[2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()
```
<img width="704" height="512" alt="Screenshot 2026-05-23 172425" src="https://github.com/user-attachments/assets/3c8c4845-c361-42bf-983f-45d2f9da648d" />














# Result:
 Include your result here
