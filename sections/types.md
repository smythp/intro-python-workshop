## Types

Types are classifications that let the computer know how a programmer inteds to use a piece of data. We've already seen one type in the last section: the integer. In this section, we'll learn four more: the floating point number, the string, the boolean, and the list.

Enter these lines as you see them below:

```
>>> type(1)
<class 'int'>
>>> type(1.0)
<class 'float'>
>>> type("Hello there!")
<class 'str'>
>>> type(True)
<class 'bool'>
>>> type([1, 2, 3])
<class 'list'>
```

Float: `1.0`

Floats are numbers with decimals, and are treated a little differently than integers.

String: `"Hello there!"`

Strings are arbitrary sets of characters, such as letters and numbers. You can think of them as a way to store text.

Boolean: `True` and `False`

Boolean is a fancy term for values representing "true" and "false," or "truthiness" and "falsiness."

List: `[1, 2, 3]`

A list is an ordered collection of values. You can put any type in a list: `["rose", "daisy", "buttercup"]` is also a valid list.

Don't worry about trying to remember these types. We'll be working with each in turn in the following sections.

### Functions



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

There are two boolean types, `True` and `False`. They are often the result of operations that compare two values. For example:

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

We'll be talking more about these five data types (strings, integers, floats, lists, and booleans) in the following sections, so don't worry about trying to remember them all now.

## What's the deal with type()?

`type()` is a function. You can think of functions in Python in a few different ways:

1. A way of doing something in Python.
2. A way of saving some code for reuse.
3. A way of taking an input, transforming that input, and returning an output. The input goes in the parentheses `()`.

These are all valid ways of thinking about functions. Soon we'll be doing more with functions, including making our own.


