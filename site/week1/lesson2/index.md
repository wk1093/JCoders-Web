# Lesson 2 - Variables, IO, and Math

[Table of Contents](../../index.md)

## Variables

### What is a variable?

A variable is a way to store data. Think of it like a box. You can put things in the box, and you can take things out of the box. You can also change what is in the box.
A variable has a name, and a value. The name is how you refer to the variable. The value is what is inside the variable.
In other languages, there is different types of "boxes" that you can use, and only certain things can go in certain boxes. In python, there is only one type of box, and you can put anything in it.

### How do I use a variable?

In Python, variables are relatively simple:
```py
my_variable = 5
```
This creates a variable called `my_variable` and sets it to the number `5`.
You can also change the value of a variable:
```py
my_variable = 5
my_variable = 6
```
Now `my_variable` is set to `6`.
You can also use variables in other places:
```py
my_variable = 5
print(my_variable)
```
This will print out `5`.
You can also use variables in math:
```py
my_variable = 5
my_variable = my_variable + 1
print(my_variable)
```
This will print out `6`.

## IO

### What is IO?

IO stands for Input/Output. It is a way to get input from the user, and a way to show output to the user.
In python, we use the `input` and `print` commands for IO.

### `print`

Print is very flexible in Python, we can put anything inside the parentheses and it will print it out.
```py
print("Hello World!")
print(5)
print(5 + 5)
print("Hello" + " " + "World!")
print("A", "B", "C", 10, 20, 30)
```

### `input`

Input is also very flexible in Python, we can put anything inside the parentheses and it will ask the user for input.
```py
a = input("Give me a random word: ")
print("Your word is", a)
```
`input` has what is called a return value. This is the value that the function returns. In this case, the return value is whatever the user types in. In this example we store the return value of `input` in a variable called `a`. Then we print out the value of `a`.

## Math

In Python, we can do math with numbers. We can add, subtract, multiply, and divide numbers.
```py
print(5 + 5)
print(5 - 5)
print(5 * 5 / 2)
```
The order of operations is the same as in math. We can also use parentheses to change the order of operations. But remember, implicit multiplication is not allowed in Python. This means that `5(5 + 5)` is not allowed. You must write `5 * (5 + 5)`.
```py
print(5 * (5 + 5))
```
We can also use variables in math:
```py
a = 5
b = 5
print(a + b)
```

## Common Errors

```py
a = input("Give me a number: ")
print(a + 5)
```
This will give an error. This is because `a` is a string. and `5` is a number. We cannot add a string and a number. We can fix this by converting `a` to a number:
```py
a = input("Give me a number: ")
a = int(a)
print(a + 5)
```
Similar to this, we cannot add a string and a number:
```py
print("23" + 5)
```
In this example, the computer has no idea that the string `23` is supposed to represent a number, because it is in a string.

[Table of Contents](../../index.md) - [Homework](../homework2/index.md)



