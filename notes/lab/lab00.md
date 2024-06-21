# Lab 00: Getting Started

## Starter files

- `lab00.py`: The template file you'll be adding your code to
- `ok`: A program used to test and submit assignments
- `lab00.ok`: A configuration file for ok

```
>>> python3 ok --local  # Run ok locally
```

## UNIX Command lines

- `ls`: Lists all files in the current directory
- `cd <path to directory>`: Change into the specified directory
- `mkdir <directory name>`: Make a new directory with the given name
- `mv <source path> <destination path>`: Move the file at the given source to the given destination

## Python Basics

### Expressions and statements

#### Expressions

An **expression** is a piece of code that evaluates to some value 

**Primitive expressions** only take one step to evaluate, including numbers and booleans

```
>>> 3
3
>>> 12.5
12.5
>>> True
True
```

**Arithmetic expressions** 

`+`, `-`, `*`, `**`, `/`, `//`, `%`, etc...

```
>>> 7 / 4
1.75
>>> (2 + 6) / 4
2.0
>>> 7 // 4        # Floor division (rounding down)
1
>>> 7 % 4         # Modulus (remainder of 7 // 4)
3
```

#### Statements

A **statement** is one or more lines of code that make something happen in a program.

An **assignment statement** consists of a name and an expression. It changes the state of the program by evaluating the expression to the right of the `=` sign and binding its value to the name on the left.

```
>>> a = (100 + 50) // 2
```