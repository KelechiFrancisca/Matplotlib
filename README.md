# Matplotlib

## Exercise 1
---
>
> Activity 1 A a trainer plot a graph of the following students scores using python
>
> Based_score = [20,40,60,70,80,100]
>
> Chioma = [70,80,90,95,30,89]
>
> David = [40,60,50,45,70,55]
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

## Exercie 2
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
