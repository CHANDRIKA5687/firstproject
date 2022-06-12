# LineGraph
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
df=pd.read_csv("/content/1. Simple linear regression.csv")
df.head()
x=np.linspace(1,150,50)
y=np.log(x)
plt.plot(x,y)
plt.grid()

plt.xlabel('SAT')
plt.ylabel('GPA')
plt.title('simple linear regression')
plt.xlim(0,100)
plt.ylim(0,5)
plt.show()
[1. Simple linear regression.csv](https://github.com/CHANDRIKA5687/firstproject/files/8885993/1.Simple.linear.regression.csv)
