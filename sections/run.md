## Running scripts

So far, you've interacted with Python one line at a time in the REPL. For the rest of this session, we're going to write and execute longer programs.

### Three ways of running scripts

Fundamentally, Python programs are just text files. You can write them in a text editor like Sublime and pass them to Python, which will execute them one line at a time. Here are three ways to run your Python programs. All work equally well, so choosing one is a matter of preference. Pick one method and stick to it for now.

#### Command line method

Open your text editor of choice (such as Sublime) and create a new file with this line:

    print("Hello world!")
	
Save it with the name `hello.py` to a known location, such as your desktop. Open your terminal and move to the desktop directory:

    $ cd Desktop
	
Once you're in the folder with your `hello.py` file, run it with:

	$ python hello.py
	Hello world!
	
As above, you should see the text `Hello world!` appear as output.


### IPython Notebook

IPython Notebooks are graphical interfaces to Python that run in the browser. To start a notebook, enter 

    $ ipython notebook
	
in your terminal. You should see messages appear in your terminal window, and your browser should open to a list of files. Once IPython is open in the browser, click `New` in the top right and select `Python` under `Notebook` from the dropdown menu.

THe IPython interface consists of cells, which can contain text or Python code. In the first cell (the blank space next to the text that says `In [ ]`, enter the text

	print("Hello world!")
	
then hit `Shift-Enter`. You should see the output `Hello world!` appear below.


### IDE

An IDE (Integrated Development Environment) is a program that can be used for both writing and running scripts, and they usually come with a number of specialized features. Python comes with its own IDE, but it only runs well on Windows and Linux, not on OSX. More powerful cross-platform IDEs for Python, such as [PyCharm](https://www.jetbrains.com/pycharm/) and [Spyder](https://pythonhosted.org/spyder/) will also allow you to write and run Python programs on your desktop. Check out these tutorials if you're interested in using an IDE to write and execute Python code:

[IDLE tutorial (not recommended for OSX)](https://www.youtube.com/watch?v=lBkcDFRA958)  
[PyCharm Quickstart](https://www.jetbrains.com/help/pycharm/2016.1/quick-start-guide.html)  
[Spyder tutorial](http://datasciencesource.com/python-with-spyder-tutorial/)  
