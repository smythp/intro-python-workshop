## Interacting with Python

To start an interactive session with Python, open your terminal and type

	$ python
	
at the prompt. 	You should see something like this

```
Python 3.5.1 |Anaconda 2.5.0 (64-bit)| (default, Dec  7 2015, 11:16:01) 
[GCC 4.4.7 20120313 (Red Hat 4.4.7-1)] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

Unlike the normal `$` terminal prompt, the Python prompt looks like this:

```
>>>
```

Keep an eye on this, as a common early mistake is entering terminal commands into the Python prompt or entering Python commands into the terminal.

### A Little Math

Let's try a little math at the Python prompt:

```
>>> 2 + 3
5
>>> 14 - 10
4
>>> 10 * 10
100
>>> 6 / 3
2
>>> 21 % 4
1
```

The first four operations above are addition, subtraction, multiplication, and division, respectively. The last operation is modulo, or mod, which returns the remainder after division.

Note the way you interact with Python at the prompt. After entering an expression such as `2 + 3`, Python "evaluates" it to a simpler form, `5`, and then prints out the answer for you. This process is called the Read Eval Print Loop, or REPL. Reading takes commands from you, the input is evaluated or run, the result is printed out, and the prompt is shown again to wait for more input. The normal terminal (the one with the `$`) is another example of a REPL. 

The REPL is useful for quick tests and, later, can be used for exploring and debugging your programs interactively.

