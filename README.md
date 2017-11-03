# TurtleArtDesign 
< img src " https://github.com/hyperrfirebreakyt/TurtleArtDesign/blob/master/python%20project.PNG " >
import turtle
turtle.bgcolor("black")
bob = turtle.Turtle()
from myFunctions import*
for times in range(1):
    turtle.colormode(255)
    bob.begin_fill()
    bob.color(47,180,48)
    bob.end_fill()
    bob.color(156,22,179)
    bob.circle(150)
    bob.left(120)
    bob.speed(30)
    turtle.colormode(255)
    bob.begin_fill()
    bob.color("brown")
    bob.color(198,189,255)
    bob.right(120)
    bob.circle(100)
    bob.right(90)
    bob.penup()
    bob.goto(-50,40)
    bob.color("purple")

for times in range(10):
    bob.forward(100)
    bob.right(50)
    bob.left(90)
    bob.backward(100)
    bob.color(10,100,255)
    bob.penup()
    bob.goto(0,100)
    bob.pendown()

    
for times in range(10):
    bob.forward(100)
    bob.right(50)
    bob.left(90)
    bob.backward(100)
    bob.color(10,100,255)
    bob.penup()
    bob.goto(0,-100)
    bob.pendown()

    
for times in range(13):
    bob.forward(100)
    bob.right(150)
    bob.speed(10)
    turtle.colormode(255)
    bob.begin_fill()
    bob.color(10,100,255)
    bob.right(60)
    bob.forward(90)
    bob.penup()
    bob.goto(230,-220)
    bob.pendown()
    bob.color("green")

for times in range(13):
    bob.forward(100)
    bob.right(150)
    bob.speed(10)
    turtle.colormode(255)
    bob.begin_fill()
    bob.color(10,100,255)
    bob.right(60)
    bob.forward(90)
    bob.penup()
    bob.goto(-255,-220)
    bob.pendown()
    bob.color("green")


for times in range(12):
    turtle.colormode(255)
    bob.begin_fill()
    bob.forward(100)
    bob.right(90)
    bob.speed(10)
    bob.color("red")
    bob.color(120,190,255)
    bob.left(120)
    bob.penup()
    bob.goto(-255,120)
    bob.pendown()
    bob.color(123,190,29)

for times in range(13):
    turtle.colormode(255)
    bob.begin_fill()
    bob.forward(100)
    bob.right(90)
    bob.speed(10)
    bob.color("red")
    bob.color(120,190,255)
    bob.left(120)
    bob.penup()
    bob.goto(255,120)
    bob.pendown()
    bob.color(123,190,29)
    









