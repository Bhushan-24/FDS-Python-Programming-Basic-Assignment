#### Q1) Write a Python program to print "Hello Python"?


```python
print("Hello Python")
```

    Hello Python
    

#### Q2) Write a Python program to do arithmetical operations addition and division.?


```python
def addition(a,b):
    return a+b
def division(x,y):
    return x/y

add=addition(10,20)
print(add)
div=division(3,9)
print(div)
```

    30
    0.3333333333333333
    

#### Q3) Write a Python program to find the area of a triangle?


```python
h=int(input('enter height of the triangle'))
b=int(input('enter base of the triangle'))
area_of_triangle=0.5*h*b
print('area of the triangle is',area_of_triangle)
```

    enter height of the triangle100
    enter base of the triangle50
    area of the triangle is 2500.0
    

#### Q4) Write a Python program to swap two variables?


```python
temp=0
a=int(input('enter a value'))
b=int(input('enter b value'))
print('Before swap',a,b)
temp=a
a=b
b=temp
print('After swap',a,b)
```

    enter a value10
    enter b value20
    Before swap 10 20
    After swap 20 10
    

#### Q5) Write a Python program to generate a random number?


```python
import random
num=random.randint(0,100)
print(num)
```

    11
    
