## Loops

Remember lists? They look like this:

	flowers = ['rose', 'violet', 'buttercup']
	
For now, let's just create a list and print it out. Our script will look like this:

```
flowers = ['rose', 'violet', 'buttercup']
print(flowers)
```

Run this script using [your chosen method](run.md). You should see the list as output.

What if we want to print out each item in the list separately? For that, we'll need something called a loop:

```
flowers = ['rose', 'violet', 'buttercup']
# print(flowers)
for flower in flowers:
    print(flower)
```

What's happening here? This kind of loop is called a "for" loop, and tells Python: "for each item in the list, do something." Let's break it down:

```
for <variable name> in <list name>:
	<do something>
```

Indented code like this is known as a "code block." Python will run the <do something> code in the code block once for each item in the list. The code in the code block doesn't have to refer to the variable at all:

```
for flower in flowers:
	print("Yay! I'm in a loop!")
```

You can also perform more complicated operations:

```
prime_numbers = [2, 3, 5, 7, 11]

for num in prime_numbers:
    print('The square of %s is:' % num)
    print(num * num)
```

