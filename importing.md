## Importing libraries

One of the main advantages of Python is that you can draw on code written by other programmers to solve a wide variety of problems. This importable code goes by a number of names, such as libraries, packages, and modules, but knowing the technical distinctions among these terms isn't that important. Python comes with a large standard library, which means that many modules are available to you without your having to install them first. In addition, Anaconda comes with another set of modules, such as NumPy, SciPy, NLTK, and Flask, that do not come with the standard Python library.

Use an `import` statement to make code from a module available in your script:

    import random
	
The above code imports the random module, which allows you to create pseudorandom numbers. Let's try it out:

```
import random

print(random.randint(1, 10))
```

Every time you run this program, you will get a different random number from 1 to 10. Notice that, in order to access the `randint` function that creates the random numbers, you need to prefix it with a dot `.` and the name of the library, like this: `random.randint(1, 10)` This is by design, since a frequent problem in programming is having variables and functions with the same name.

When you import a module, Python creates a "namespace" for that module. You can access objects within that namespace with the `.` syntax, like we did with `random.randint`.

In the next (and last) section, we'll use the `random` module to create a fortune cookie script that will pront some motivational (or demotivational) aphorisms.
