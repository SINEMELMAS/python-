# python-
import numpy as np
import pandas as pd

print(pd.Series([2,4,6]))
print("------------")

data = {'number': [2, 4, 6],'sqr': [4, 16, 36]}
dataframe = pd.DataFrame(data)
print(dataframe)
print("------------")

a=[22,21,23]
b=["sinem","hatice","fatma"]
for i in range(len(a)):
    print(a[i],":", b[i])
print("------------")

print(pd.Series(data=a,index=b))


