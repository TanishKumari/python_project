import numpy as py
import pandas as pd
import matplotlib.pyplot as plt 
import seaborn as sns
df=pd.read_csv("flowers.csv")
df.info()
print(df)
plt.hist(df,histtype="bar")
plt.label("bar chart")
plt.xlabel("x axis")
plt.ylabel("y axis")
plt.show()


# python_project
