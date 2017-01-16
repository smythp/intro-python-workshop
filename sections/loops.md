## Lists and Loops

### Lists

Remember lists? They look like this:

	flowers = ['rose', 'violet', 'buttercup']
	
For now, let's just create a list and print it out. Our script will look like this:

```
flowers = ['rose', 'violet', 'buttercup']
print(flowers)
```

Save this to a new file called `loop.py` and run it with `python loop.py`. You should see the list printed out in the terminal.

So far, we've only learned one function: `type()`. Let's try out another:

```
flowers = ['rose', 'violet', 'buttercup']
# print(flowers)

list_length = len(flowers)

print(list_length)
```

The `len()` function returns the number of items in a list or the number of characters in a string.

Notice that, if you run the code above, you won't see the `flowers` list printed out. That's because that line has become a comment. If you put a `#` (hash or pound) at the beginning of a line, that line will be ignored.

### Loops

What if we want to print out each item in the list separately? For that, we'll need something called a loop:

```
flowers = ['rose', 'violet', 'buttercup']
# print(flowers)
for flower in flowers:
    print("My favorite flower is the", flower)
```

What's happening here? This kind of loop is called a "for" loop, and tells Python: "for each item in the list, do something." Let's break it down:

```
for <variable name> in <list name>:
	<do something>
```

Indented code like this is known as a "code block." Python will run the <do something> code in the code block once for each item in the list. You can also refer to <variable name> in the <do something> block.

You can also perform more complicated operations:

```
prime_numbers = [2, 3, 5, 7, 11]

for num in prime_numbers:
    print('The square of %s is:' % num)
    print(num * num)
```

