## Running scripts

So far, you've interacted with Python one line at a time in the REPL. For the rest of this session, we're going to write and execute longer programs.

### Your first script

Open your text editor of choice (such as Sublime) and create a new file with this line:

    print("Hello world!")
	
Save it with the name `hello.py` to a known location, such as your desktop. Open your terminal and move to the desktop directory:

    $ cd Desktop
	
Once you're in the folder with your `hello.py` file, run it with:

	$ python hello.py
	Hello world!
	
As above, you should see the text `Hello world!` appear as output. 

Congratulations! You've written your first script.

### A Note on Text

Fundamentally, Python programs are just text files. You can write them in any text editor, like Sublime Text or Notepad on Windows. When you pass the text file to Python, it runs the code in the file one line at a time. There's nothing special about `.py` files, they're just regular text files. This makes them work well with command line tools like Git. The tools you've learned so far—the command line, Git, markdown, grep, Sublime—are all designed to work well together, and the medium through which they all work is plain text.
