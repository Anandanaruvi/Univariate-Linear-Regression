# Implementation of Univariate Linear Regression

## Aim:

To implement univariate Linear Regression to fit a straight line using least squares.

## Equipment’s required:

1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

1.	Get the independent variable X and dependent variable Y.

2.	Calculate the mean of the X -values and the mean of the Y -values.

3.	Find the slope m of the line of best fit using the formula.
 ![eqn1](./eq1.jpg)
 
4.	Compute the y -intercept of the line by using the formula:
![eqn2](./eq2.jpg)  

5.	Use the slope m and the y -intercept to form the equation of the line.

6.	Obtain the straight line equation Y=mX+b and plot the scatterplot.

## Program
```
import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1])) 
```
## Output

![MULTIV](https://user-images.githubusercontent.com/120443233/215506889-cf1e193f-55bd-43b6-9a30-73ef6583f836.png)




## Result

Thus the univariate Linear Regression was implemented to fit a straight line using least squares.
