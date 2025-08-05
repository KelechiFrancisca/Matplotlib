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
