## A Little Motivation

Early on, we learned a bit about lists, which look like this:

    ['rose', 'violet', 'buttercup']
	
We're going to create a small application that will print a random motivational saying every time a user presses `Enter`. Our first step will be to create a list of positive sayings:

```
motivational_phrases = [
	"Importing modules is easy!"
	"You look awesome today!",
    "You write lists like a pro!"
    ]
```

Lists open with a square bracket `[`, have items seperated with commas, and end with a square bracket `]`, like this:

    [1, 2, 3, 4, 5]
	
Our positivity list above spreads the list out over multiple lines for greater readability, which is allowed in Python. Remember that you can change the strings in the list to whatever phrases you choose.

### Importing a module

Now that we have our sayings, let's use it in conjunction with some functionality from a module that's built into Python: the `random` module.

```
import random

motivational_phrases = [
	"Importing modules is easy!"
	"You look awesome today!",
    "You write lists like a pro!"
    ]

print(random.choice(motivational_phrases))
```

The `random.choice` function chooses a random item from a list and returns it. The `.` syntax indicates that the function is coming from the `random` library.

As with our weather app, this positive saying generator could be improved by making it so the program doesn't have to run again every time to get new output. Let's add a while loop for the final version:

```
while True:
    import random

    motivational_phrases = [
        "You look awesome today!",
        "You're a Python prodigy!",
        "You write lists like a pro!"
        ]

    print(random.choice(motivational_phrases))
    input()
```	

The empty `input()` statement at the end means that the user has to hit `Enter` again in order to see a new phrase.
