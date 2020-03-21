# Installation

Python is a program like any other.  It takes our commands and interprets them into something the computer can run.

So, before learning Python we must first install it.

The details of this vary significantly but on Windows I personally find it easiest to install Windows Subsystem for Linux.

As the name suggests, this is a compatibility layer between Windows and Linux that allows us to do Linux-like commands in a Windows environment.

It also happens to come with all the programs we need baked in. 

So, go ahead and follow the [install guide](https://wsl-guide.kennethreitz.org/en/latest/installation.html) for WSL and come back once it's ready to go.

# Testing Our Setup

Okay, we've now installed Windows Subsytem for Linux.  This lets us run Linux commands in Windows, like Python and Git (we'll get to this in a bit).

Now, let's test out our installation.

In the WSL command prompt, type `python3 --version`.

You should see some information about what eversion of `python3` is installed with WSL, and it should be >=3.6.

Next, type `git --help`.  Some similar information for our version of git should be displayed.

## What *are* Python and Git?

We've got this stuff installed, but we don't really know what it is yet.  Let's start with Python.  Python has an interpreter whose job it is to take the code we write and *interpret* it into something the computer can understand - the right one's and zero's.  There are a great many things that go into making that happen, but the beauty of it is that we simply don't care.  We are going to ask Python to do some things for us, and then it will do whatever is required with the one's and zero's to make that happen.  

With that in mind, what we are really doing is running the Python interpreter program on a particular file that contains Python code.  It would be nice to perform some simple examples, but we need code to make that happen.  So, how do we download code?

Enter Git.  Git is a tool created for storing, sharing, and discussing source code - in all languages.  Why not use Google docs, you ask?  Well, we don't write code like we write documents.  You will soon see that the format doesn't lend itself well to something like Microsoft Word - we'll get you a proper text editor soon.  More importantly, we really don't want people modifying the code at the same time - this would be an absolute nightmare to deal with.  But, we really need to see who made modifications when in case somebody broke something - looking at you, *Kevin*.  

So, git allows us to edit our code locally and run whatever tests against it our required.  When we're done, we push it back upstream to the remote repository so that it is stored safe and sound.  

GitHub is a popular website that implements Git for us.  You will need an account there to download the code.  Please visit [Github](https://github.com/) and follow the signup links.  Return back here once you are done.

When you are ready to try git, type `git clone https://github.com/nfrancque/python-for-noobs.git` on your command line.  This will download the code immediately!  See how easy that was?

This now lets us try out our Python interpreter.  Let's ask it to interpret the file `helloworld.py` in the current directory.  Type `python3 helloworld.py`.  It will print 'Hello, World!', proving to us that Python has read our code and done something useful with it (well, sort of useful).

Ready for something bigger?

