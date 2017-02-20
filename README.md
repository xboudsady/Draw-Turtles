# Draw-Turtles
Short tutorial exercise from Udacity on using classes to build object, along with class methods.

Using Python, and the turtle class.

#import turtle

def draw_square(some_turtle):
    for i in range (1, 5):
        some_turtle.forward(100)
        some_turtle.right(90)

def draw_art():
    window = turtle.Screen()
    window.bgcolor("red")

    #Create the turtule Brad - Draws a square
    brad = turtle.Turtle()
    brad.shape("turtle")
    brad.color("yellow")
    brad.speed(2)
    for i in range(1,36):
        draw_square(brad)
        brad.right(10)
    

    #Create the turtle Angie - Draws a circle
    #angie = turtle.Turtle()
    #angie.color("blue")
    #angie.shape("arrow")
    #angie.circle(100)

    window.exitonclick()


#draw_art()
