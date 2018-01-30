import turtle

wn = turtle.Screen()
lovelace = turtle.Turtle()

# move the turtle forward a little so that the whole path fits on the screen
lovelace.penup()
lovelace.forward(60)

# now draw the drunk pirate's path
lovelace.pendown()
for angle in [160, -43, 270, -97, -43, 200, -940, 17, -86]:

    # we use .left() so that positive angles are counter-clockwise
    # and negative angles are clockwise
    lovelace.left(angle)
    lovelace.forward(100)

wn.exitonclick()
