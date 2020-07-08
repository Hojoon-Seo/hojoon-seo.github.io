# Hojoon Seo

# Welcome to my blog

## 2020/09/06
I forgot to upload my blog yesterday. But today, I will upload a python challenge from w3resource. I solved the problem below by the code below the challenge.

## Question: Write a python program to check if a given positive integer is a power of four.

```
number = int(input("What number do you chose?: "))
i = 0
while 3**i < number + 1:

    if 3**i == number:
        print("Yes")
    else:
        print("No")
    
    i += 1
```

## 2020/07/06

![My turtle picture 1](.\Turtle_picture_1.png)

This picture was created by the turtle function of Python. The code is as follows:

```
import turtle
t = turtle.Turtle()
s = turtle.getscreen()
t.speed(0)
t.shape("turtle")
s.bgcolor("pink")
s.tracer(0)
for i in range(100):
    t.color("blue")
    t.fd(57)
    t.left(46)
    t.color("red")
    t.fd(34)
    t.setpos(0,2)
    t.circle(50)
turtle.done()

```

## 2020/07/05

Today I met my friends and had a farewell party for a friend.

## 2020/07/04 

Today, finally the weather is nice and sunny.

## 2020/07/03

Today my Airpods Pro arrived from Korea.

## 2020/07/02

Today the weather was cloudy and dark. 

## 2020/07/01

Today in my lesson, I learned about the define function. I could define my own commands and use them; for instance:

```
def rectangle_area_calculator(width,height):

    area = height*width

    print(area)

    return area
```

## 2020/06/30

Today the weather was nice. I had a nice day.


## 2020/06/29
```
n = 30

number = n

for i in range(1,31):

    if i%3 == 0 and i%5 == 0:

        print("Fizz Buzz")

    elif i%3 == 0:

        print("Fizz")

    elif i%5 == 0:

        print("Buzz")

    else:

        print(i)
```

This is my Fizz Buzz program. When a number is a multiple of 3, the program prints Fizz. When a number is a multiple of 5, the program prints Buzz. When a number is both a multiple of 3 and 5, the program prints Fizz Buzz. However, when a number is nor a multiple of 3 and 5, the program prints the number. 

