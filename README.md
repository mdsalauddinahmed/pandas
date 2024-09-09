# pandas
## Series:
It is define as a one-dimensional array that is capable of storing various data types
import pandas as pd
a=pd.Series([1,2,3,4,5])
print(a)

x=[2,3,4,5,6,7,8]
var=pd.Series(x)
print(var)

x=[2,3,4,5,6]
var=pd.Series(x, index=['a','b','c','d','e'] ,dtype="float",name="python")
print(var)

dic = {"name":["python","c","java"],"por":[12,13,14],"rank":[1,4,2]}
var =pd.Series(dic)
print(var)

s1=pd.Series(12,index=[1,2,3,4,5,6])
s2=pd.Series(12,index=[1,2,3,4,5,6,7,8,9])
print(s1+s2)

## DataFrame

