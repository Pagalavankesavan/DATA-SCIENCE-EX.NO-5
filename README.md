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
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
marks = [13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student Name')
plt.show()

student = ['A','B','C','D']
attendence = [90,85,73,88]
plt.plot(student,attendence)
plt.xlabel('Attendence')
plt.ylabel('student Name')
plt.show()
```
<img width="758" height="475" alt="b1" src="https://github.com/user-attachments/assets/5f4d0049-f9ad-4bea-b4f5-addb5f91efa1" />
<img width="734" height="487" alt="b2" src="https://github.com/user-attachments/assets/15f0afb5-2d0a-40cc-bce6-85a03a946f1f" />
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
<img width="917" height="585" alt="image" src="https://github.com/user-attachments/assets/026122fa-43d0-41ad-b3b0-7f9c36acbec8" />
<img width="963" height="637" alt="image" src="https://github.com/user-attachments/assets/6faa062f-aeee-4642-bc21-2fa95cff90ba" />

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
<img width="819" height="578" alt="image" src="https://github.com/user-attachments/assets/48f976b7-247f-4386-99af-a4f2ef8686b3" />
<img width="794" height="584" alt="image" src="https://github.com/user-attachments/assets/2f7d1c1d-2aa9-46c8-b8a4-65ef77233a8d" />

```
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
<img width="1043" height="671" alt="image" src="https://github.com/user-attachments/assets/749a6bcf-270f-4c5d-9feb-10bb26d34638" />

# Result:
Thus, all the data visualization techniques of matplotlib has been implemented.
