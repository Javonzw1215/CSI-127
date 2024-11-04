# CSI-127
#Javon Zaire Washington
#Javon.Washington76@myhunter.cuny.edu

import turtle
turtle.colormode(255)
trey = turtle.Turtle()
trey.shape("turtle")
trey.backward(100)

# Loop to create varying pen sizes and shades of blue
for i in range(0, 255, 10):
    trey.forward(10)
    trey.pensize(i)
    trey.color(0, 0, i)  # Set color to shades of blue (R=0, G=0, B=i)

