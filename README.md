# Matplotlib

## Exercise 1
---
>
> Activity 1 A a trainer plot a graph of the following students scores using python
>
> Based_score = [20, 40, 60, 70, 80, 100]
>
> Chioma = [70, 80, 90, 95, 30, 89]
>
> David = [40, 60, 50, 45, 70, 55]
---
>
## Answer:
>
> import pandas as pd
>
> import numpy as np
>
> import matplotlib.pyplot as plt
---
>
> plt.plot(based_score, Chioma,color='red', marker='o', label='Chioma')
>
> plt.plot(based_score, David, marker='x',color='purple', label='David')
>

> plt.title("A Graph of Students score")
> 
> plt.ylabel("Main score")
> 
> plt.xlabel('Students Scores')


> plt.legend()

> plt.close
---
<img width="562" height="455" alt="v1" src="https://github.com/user-attachments/assets/a6d4a3f2-797f-401d-902b-1a43de7c203c" />




## Exercise 2
---
>
> Activity 2 Given the following data for multiple lines
>
> x = [1, 2, 3, 4, 5]
>
> y1 = [1, 4, 9, 16, 25]
>
> y2 = [1, 2, 3, 4, 5]
>
> y3 = [2, 8, 20, 25, 30]
---
>
## Answer:
>
> plt.plot(x, y1, marker ='o', color = 'green', linestyle = 'dashed', markersize =15, label = 'Y1 graph')
>
> plt.plot(x, y2, marker ='o', color = 'purple', linestyle = 'dashed', markersize =15, label = 'Y2 graph')
>
> plt.plot(x, y3, marker ='o', color = 'red', linestyle = 'dashed', markersize =15, label = 'Y3 graph')

>
> plt.title("A Graph of x and y")
>
> plt.ylabel("Y Axis")
>
> plt.xlabel("X Axis")
>
> plt.legend()
---
<img width="562" height="455" alt="v2" src="https://github.com/user-attachments/assets/45caa856-5e02-4db6-b213-8b5944427e28" />




## Exercise 3
----
> Activity 3 Given the set of dataset, plot a bar, pie, histogram, scatter and subplot with py.
---
## Answer:
>
# Creating a Bar Chart

>
>
> courses = ['Math', 'Science', 'History', 'English',]
>
> students = [40, 35, 30, 50]

>
# Plotting bar
> plt.bar(courses, students)
>
> plt.title ('A bar Graph')
>
> plt.ylabel('Students')
>
> plt.xlabel('Courses')
>
> plt.show()
---
>
# Creating a Pie Chart


> # pie chart
> 
> devices = ['Laptops','Mobiles','Tablets']
>
> sales = [200, 500, 100]

>
> plt.pie(sales, labels=devices, autopct="%1.2f%%")
>
> plt.show()
---
>
# Creating a Histogram Chart

>
> data = np.random.randn(1000)

>
> scores = [56, 78, 90, 45, 77, 65, 88, 92, 67, 70, 82]

# plotting histogram
>
>plt.hist(data, bins=40, egdecolor='black')

>
>plt.title('distribution of scores')
>
>plt.show()
---

```python
# histogram

data = np.random.randn(1000)

scores = [56, 78, 90, 45, 77, 65, 88, 92, 67, 70, 82]

# plotting histogram
plt.hist(data, bins=40, edgecolor='black')
plt.title('distribution of scores')
plt.show()

```
<img width="667" height="605" alt="v10" src="https://github.com/user-attachments/assets/6e0d35f0-831a-40f9-911a-8a5af24edd1e" />



>
# Creating a Scatter Plot

>
# scatter plot
>
> height = [150, 160, 165, 170, 175, 180, 155]
>
> weight = [50, 55, 60, 65, 70, 75, 52]

> plt.scatter(height, weight)
> plt.title(('Investigating relationship between height and weight')
> 
> plt.show()
---


>
# Creating a Subplot Chart
>
>
# subplot

> x = [1, 2, 3, 4, 5]
>
> y1 = [1, 4, 9, 16, 25]
> 
> y2 = [1, 2, 3, 4, 5]
> 
> fig, (fig1, fig2) = plt.subplots(2,1)

>
# creating subplot 
>
> fig1.plot(x, y1, color ='red', marker='o')
>
> fig1.set_title('Chioma record')

>
# fig 2
>
> fig2.plot(x, y2, color ='purple', marker='x')
>
> fig2.set_title('David record')

# general title
>
> fig.suptitle('A Sunplot Diagram')

>
>plt.show()
