import turtle

# Налаштування черепахи
t = turtle.Turtle()
t.speed(0)
t.pensize(2)

# Малювання будинку
t.penup()
t.goto(-200, -100)
t.pendown()

# Стіни
t.forward(100)
t.left(90)
t.forward(200)
t.left(90)
t.forward(100)
t.left(90)
t.forward(200)
t.left(90)

# Дах
t.penup()
t.goto(-200, 100)
t.pendown()
t.right(45)
t.forward(141)
t.left(90)
t.forward(141)
t.left(135)

# Дерево
t.penup()
t.goto(100, -100)
t.pendown()

# Стовбур
t.forward(100)

# Гілки
t.left(45)
t.forward(50)
t.right(90)
t.forward(30)
t.left(180)
t.forward(60)
t.right(90)
t.forward(30)
t.left(135)

t.hideturtle()
