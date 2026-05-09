# -Rotating-Square-Art
    import turtle
# Screen setup
screen = turtle.Screen()
screen.bgcolor("black")

# Turtle setup
t = turtle.Turtle()
t.color("white")
t.speed(0) # Sobcheye beshi speed-er jonno 0 deya hoyeche

counter = 0
while counter < 36:
    # Ekti square bananor jonno loop
    for i in range(4):
        t.forward(100)
        t.right(90)
    
    # Proti ti square-er por turtle-ke 10 degree ghuranu hoyeche
    t.right(10)
    counter += 1

# Screen-e click korle bondho hobe
turtle.exitonclick()        

My second project
