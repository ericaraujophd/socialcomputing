# Turtles

Turtles are the kind of agents you will use most of the time. This tutorial will walk you through the commands that permit you to create and manipulate turtles in your model.

We will also cover the properties of turtles, which are the attributes that define their behavior and appearance. Turtles can have different shapes, colors, and sizes, and you can use these properties to represent different types of agents in your model.

## Creating Turtles

To create turtles in your model, you can use the `create-turtles` command. This command creates a specified number of turtles and assigns them random properties. For example, the following command creates 10 turtles:

```scheme
create-turtles 10
```

This command creates 10 turtles with random properties. You can also specify the properties of the turtles when you create them. For example, the following command creates 10 turtles with a specific color and shape:

```scheme
create-turtles 10 [
  set color red
  set shape "circle"
]
```

This command creates 10 turtles with the color red and the shape of a circle. You can also use the `set` command to change the properties of turtles after they are created. For example, the following command changes the color of all turtles to blue:

```scheme
ask turtles [
  set color blue
]
```

## Moving Turtles

To move turtles in your model, you can use the `fd` (forward) and `bk` (backward) commands. These commands move turtles a specified distance in the direction they are facing. For example, the following command moves all turtles forward 10 steps:

```scheme
ask turtles [
  fd 10
]
```

This command moves all turtles forward 10 steps. You can also use the `rt` (right turn) and `lt` (left turn) commands to change the direction of turtles. For example, the following command turns all turtles right 90 degrees:

```scheme
ask turtles [
  rt 90
]
```

This command turns all turtles right 90 degrees. You can also use the `set heading` command to set the direction of turtles to a specific angle. For example, the following command sets the heading of all turtles to 45 degrees:

```scheme
ask turtles [
  set heading 45
]
```

## Changing Turtles' Properties

To change the properties of turtles, you can use the `set` command. For example, the following command changes the color of all turtles to green:

```scheme
ask turtles [
  set color green
]
```

This command changes the color of all turtles to green. You can also use the `set` command to change other properties of turtles, such as size and shape. For example, the following command changes the size of all turtles to 2:

```scheme
ask turtles [
  set size 2
]
```

This command changes the size of all turtles to 2. You can also use the `set` command to change the shape of turtles. For example, the following command changes the shape of all turtles to a square:

```scheme
ask turtles [
  set shape "square"
]
```

This command changes the shape of all turtles to a square. You can also use the `set` command to change other properties of turtles, such as color and heading. For example, the following command changes the color of all turtles to red:

```scheme
ask turtles [
  set color red
]
```

This command changes the color of all turtles to red. You can also use the `set` command to change other properties of turtles, such as size and shape. For example, the following command changes the size of all turtles to 2:

```scheme
ask turtles [
  set size 2
]
```

This command changes the size of all turtles to 2. You can also use the `set` command to change other properties of turtles, such as color and heading. For example, the following command changes the color of all turtles to red:

```scheme
ask turtles [
  set color red
]
```

