# Draw-Square-using-python-turtle-
Draw Square pattern with four different colors using for loopusing python turtle🐢


import turtle

# Fullscreen the canvas
screen = turtle.Screen()
screen.setup(1.0, 1.0)

# Begin!
t = turtle.Turtle()

for c in ['red', 'green', 'blue', 'yellow']:
  t.color(c)
  t.forward(75)
  t.left(90)

screen.mainloop()
