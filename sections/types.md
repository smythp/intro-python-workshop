## Types

### What was "print"?

The `print()` statement you used in the last section is an example of a function. We'll talk more about functions later, but for now you can think of them as actions that are performed on a piece of data. The `print()` function operates on the data within the parentheses by printing that data to the screen.

Let's try out another function that will help us to learn more about the kinds of data available to us in Python:

	type("I am a string!")

Try this out in the REPL by opening your terminal and typing `python`, then entering the above line at the `>>>` prompt. You should see something like this:

```
Python 3.5.1 (default, Mar 26 2016, 19:04:22) 
[GCC 4.8.2] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> type("I am a string!")
<class 'str'>
```

The `<class 'str'>` indicates that our text in quotes is a string. A string is a data type that contains arbitrary characters, such as letters, numbers, and special symbols like `!` and `&`. 

In programming, data is stored in a number of ways, called "types."  Let's try a number of them out:

```
>>> type(5)
<class 'int'>
>>> type(5.0)
<class 'float'>
>>> type([1, 2, 3])
<class 'list'>
>>> type(True)
<class 'bool'>
>>> type(print)
<class 'builtin_function_or_method'>
```

The types above are integers, floating point numbers, lists, booleans, and functions.

Integers are numbers without decimals, while floating point numbers are numbers with decimals.

Lists are ordered collections of other objects, such as `[1, 2, 'ham', 'eggs']`, which is a list containing two integers and two strings. 

There are two boolean types, `True` and `False`. They are often the result of operat compare two values. For example:

```
>>> 10 > 5
True
>>> 10 < 5
False
>>> 1 == 1
True
>>> 1 == 3
False
```

We'll be talking more about these five data types (strings, integers, floats, lists, and booleans) in the following sections.
