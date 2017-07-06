# Shapes-Python
Trying to draw shapes using Python turtle library.

from turtle import *
import math

# Name your Turtle.
t = Turtle()

# Set Up your screen and starting position.
setup(500,300)
x_pos = 0
y_pos = 0
t.setposition(x_pos, y_pos)
pencolor("blue")
pendown()
forward(100)
left(90)
forward (100)
left(90)
forward(100)
left(90)
forward(100)

penup()
goto(-100,100)
pencolor("purple")
pendown()
forward(100)
left(120)
forward (100)
left(120)
forward(100)



### Write your code below:









# Close window on click.
exitonclick()
